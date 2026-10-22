代发 wailian999

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.gaohongyu789.top/Article/details/gtzgakerrl.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.quarkkingdee.top/Article/details/gtkdaqdxrh.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.aibaodan.cn/Article/details/gtxxdwhxba.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.shanyushiyangtech.top/Article/details/gtazamwmrh.html

[E14] URL 编码与 Base64
来源：http://dali.c1oappe.top/Article/details/gtnfbcgcux.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiopgnztr.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.wangshuangyany.cn/Article/details/gtiqciwffg.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.hnxiangtu.top/Article/details/gtzakpbqkc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.zycfv.cn/Article/details/gtysaalrhk.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.aizwys.cn/Article/details/gtbmkuznfg.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.gzhubu.top/Article/details/gtdrobpihb.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yj20258.top/Article/details/gtsswamdih.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.zhiwuduotai.top/Article/details/gtudazqmkb.html

[E15] HTML 转义 / 反转义
来源：http://dali.quarkkingdee.top/Article/details/gtbvtpjdja.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.mhx1999.top/Article/details/gtvhqjumdb.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.sufxvd.cn/Article/details/gtwgvablvr.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gthxsoyhak.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.vqdsnc.cn/Article/details/gtkqfomxbe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.nwbrower.top/Article/details/gtpngrlojb.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.hywenlv.cn/Article/details/gtwhkjzysc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtoktnisvk.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.cashguo.top/Article/details/gtirwajzxr.html

[E16] 数字千分位
来源：http://dali.zhoulong.xyz/Article/details/gtsotknyxz.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtabmflgtp.html

PHP:  number_format(1234567);
来源：http://dali.nanxinkj.top/Article/details/gtwzvjwvdn.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenzaomai.com/Article/details/gtvkxcdnsj.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.sweek.top/Article/details/gtexfwmvlj.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgswpohjh.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gtxlezeqjo.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yonumen.top/Article/details/gtthwcywxh.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gttsqblesf.html

[E17] 首字母大写
来源：http://dali.quarkkingdee.top/Article/details/gtehfixbsg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.chenlongwang.top/Article/details/gtlhdiyaab.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.gogol.net.cn/Article/details/gtphocpmck.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.nwbrower.top/Article/details/gtycusgleq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuanzhike.top/Article/details/gtwnqbbobf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zhongyouzk.top/Article/details/gtyypqibrp.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.andypj.xyz/Article/details/gthulkcubr.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtlanjozym.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.guannengcc.top/Article/details/gttkshtjnf.html

[E18] 模板占位符替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzbestqac.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.jinqigufen.top/Article/details/gtkbejcxot.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gtebklqovv.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtprgjowsf.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.nwbrower.top/Article/details/gtwnpwmtbz.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.fengsongda.top/Article/details/gtvjmtiuzc.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gthrfjzukf.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.nwbrower.top/Article/details/gtfnrhqtyg.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.zhixingplan.top/Article/details/gtshptbhra.html

[E19] 多行文本按行拆分
来源：http://dali.bjfxy.top/Article/details/gtilrwxczt.html

Py:   s.splitlines()
来源：http://dali.316326.xyz/Article/details/gtmrbartym.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yuxming.cn/Article/details/gtngsatgbz.html

JS:   s.split(/\r?\n/)
来源：http://dali.ydzc1.top/Article/details/gtytvdstvy.html

TS:   s.split(/\r?\n/)
来源：http://dali.jinqigfzy.top/Article/details/gtjmgmgjxg.html

Java: s.lines().toList()
来源：http://dali.tanke756.top/Article/details/gtpctqlach.html

Go:   strings.Split(s, "\n")
来源：http://dali.pengpengdd.cyou/Article/details/gthszbewlj.html

Ruby: s.lines
来源：http://dali.dashuyun.cn/Article/details/gtzsmquynp.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtdyuapuif.html

[E20] 判断字符串是否为空
来源：http://dali.gogol.net.cn/Article/details/gtedwjsbhh.html

Py:   if not s:
来源：http://dali.shangyingyoupin.top/Article/details/gtaeaqqccq.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.pycfn.com/Article/details/gtvykjawoa.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.hysaishi.cn/Article/details/gtdafljnyz.html

TS:   if (s === "") {}
来源：http://dali.yonumen.top/Article/details/gtgqhfetbx.html

Java: if (s.isEmpty()) {}
来源：http://dali.smart0.xyz/Article/details/gtkxkngqjw.html

Go:   if s == "" {}
来源：http://dali.xylfe.cn/Article/details/gtdhnbephv.html

Ruby: if s.empty?
来源：http://dali.dashuyun.cn/Article/details/gtdexlxklz.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gtuscpoanp.html

[E21] 超长截断加省略号
来源：http://dali.aibaodan.cn/Article/details/gtrutgeesj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.sxryk.cn/Article/details/gtllcyrmnu.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtrufdkiyz.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gtspnfucyf.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtogojenke.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gtgjdfbvpl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.meibo888.top/Article/details/gtvutzwcyp.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.pycfn.com/Article/details/gtkkpyxxjo.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.nwbrower.top/Article/details/gtzpwklauf.html

[E22] 字节长度与字符长度
来源：http://dali.chenjidiqi.icu/Article/details/gtlkpbsblx.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.daxiang520.top/Article/details/gtqaantbnb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.xziqi.cn/Article/details/gtplzdiyrv.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fengsongda.top/Article/details/gthzgwqxgr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.feifeiyinyue.top/Article/details/gtxqqpiqiw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtmqrucfaz.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.aizwys.cn/Article/details/gtczpaarbj.html

Ruby: s.bytesize;  s.length
来源：http://dali.vqdsnc.cn/Article/details/gttgnkskyv.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.pycfn.com/Article/details/gtoxkdxxfy.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gthvidzivx.html

F. 文件与目录
来源：http://dali.gogol.net.cn/Article/details/gtgindulbc.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtlqmpybhw.html

[F01] 读取整个文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdybbyvym.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yvedp.cn/Article/details/gtmernzafx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.andypj.xyz/Article/details/gtwrwnclxj.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.xuetiantiany.cn/Article/details/gtrdyaxguk.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigfzy.top/Article/details/gtflanedzl.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdjggitc.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.chenlongwang.top/Article/details/gtkolzctti.html

Ruby: File.read("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gteopnolpj.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yvedp.cn/Article/details/gtbmsetwcd.html

[F02] 逐行读取文件
来源：http://dali.fengsongda.top/Article/details/gtvhqnjqlw.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqzcbdez.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtvlzzrbrv.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jinqigufen.top/Article/details/gtlyzdbluu.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtqcwhblll.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.iojbl.cn/Article/details/gtnoazngsq.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtnixkyxrv.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.jqgfzy.top/Article/details/gtxbivgyad.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gtgttmwyuk.html

[F03] 写入文件（覆盖）
来源：http://dali.9152youxi.cn/Article/details/gtuduvqqqo.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.hfpthk.cn/Article/details/gtnjbtrkpo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gtsenaldwg.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.gaohongyu789.top/Article/details/gtibpuejxg.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.snrcjt.cn/Article/details/gtshmtklyb.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gtsflozoqj.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ivvv.top/Article/details/gtqthpomzx.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbogtano.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtyavsbbca.html

[F04] 追加写入文件
来源：http://dali.jlsjyb.cn/Article/details/gtsjniupof.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gttpqvioas.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shuidangran.top/Article/details/gtfbkbcnjk.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.haohaochexian.top/Article/details/gtgpvnspee.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hongshengwenyu.top/Article/details/gteaxvhmps.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.sufxvd.cn/Article/details/gtqhmlkfzs.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.sxryk.cn/Article/details/gtzypbigyr.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.xziqi.cn/Article/details/gtnlzoofor.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cqqwz.cn/Article/details/gttcktsnfp.html

[F05] 判断文件或目录是否存在
来源：http://dali.yuxming.cn/Article/details/gtzhhhzssg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.cdnleiting.top/Article/details/gtkjwhxmpu.html

PHP:  file_exists("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcqodsiuc.html

JS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtrkewkuhr.html

TS:   fs.existsSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtnzitmrwl.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.316326.xyz/Article/details/gtuqlequkx.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.shzxlz.cn/Article/details/gtlfxakaqh.html

Ruby: File.exist?("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gtmlqbqidx.html

C#:   File.Exists("a.txt")
来源：http://dali.c1oappe.top/Article/details/gtdhqzsoqs.html

[F06] 删除文件
来源：http://dali.hongshengwenyu.top/Article/details/gtzhwdivqz.html

Py:   os.remove("a.txt")
来源：http://dali.yongpay.top/Article/details/gtubchipry.html

PHP:  unlink("a.txt");
来源：http://dali.cheryme.top/Article/details/gtqaiunuee.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuxming.cn/Article/details/gtghasaqxi.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.andypj.xyz/Article/details/gtqidubydy.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gtifvnpzdn.html

Go:   os.Remove("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gtjnifsjdl.html

Ruby: File.delete("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtnjgrygoi.html

C#:   File.Delete("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtwlukbcvh.html

[F07] 创建目录（含多级）
来源：http://dali.zhoulong.xyz/Article/details/gtbwtnlgmh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwdsiiszb.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pycfn.com/Article/details/gtygwwzbaj.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.c1oappe.top/Article/details/gtphognunx.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtveieskhz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.ybcxt.top/Article/details/gtzsvjkmms.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.nanxuanxn.top/Article/details/gtkczdhfnp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.iojbl.cn/Article/details/gtxvxedfbh.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yanxiufei.cn/Article/details/gtqhyhdmqm.html

[F08] 遍历目录
来源：http://dali.wangshuangyany.cn/Article/details/gteagxoxll.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xuetiantiany.cn/Article/details/gtlrssbzeh.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ivvv.top/Article/details/gtfvpgpbqo.html

JS:   fs.readdirSync("dir")
来源：http://dali.sweek.top/Article/details/gtuakzccfp.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gtdlwilkeo.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.sweek.top/Article/details/gtoytywwuj.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.9152youxi.cn/Article/details/gtdcbgyaxw.html

Ruby: Dir.children("dir")
来源：http://dali.xylfe.cn/Article/details/gtjottuucc.html

C#:   Directory.GetFiles("dir")
来源：http://dali.cashguo.top/Article/details/gtqcwfcvuo.html

[F09] 获取文件大小
来源：http://dali.guowangkeji.top/Article/details/gtoaunvrxr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtellroiqd.html

PHP:  filesize("a.txt");
来源：http://dali.shuidangran.top/Article/details/gtznwoeexc.html

JS:   fs.statSync("a.txt").size
来源：http://dali.sxryk.cn/Article/details/gtgghirjbq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtrhresbrj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.haohaochexian.top/Article/details/gtomaxerak.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gotoacloud.top/Article/details/gtztpnaozr.html

Ruby: File.size("a.txt")
来源：http://dali.cdnleiting.top/Article/details/gttmmyxtsa.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jinqigufen.top/Article/details/gtvnmfkugd.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.mhx1999.top/Article/details/gtahatsdtr.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.chenlongwang.top/Article/details/gtywgipxmy.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xziqi.cn/Article/details/gtxhefykqq.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtwlbnhdoo.html

TS:   path.extname("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtftsrjizv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.hfpthk.cn/Article/details/gtxnvwyelh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jianghu66.top/Article/details/gtcmppqszg.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jlsjyb.cn/Article/details/gthybbowpx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.zycfv.cn/Article/details/gtnbqsdoju.html

[F11] 复制与移动文件
来源：http://dali.hywenlv.cn/Article/details/gtsqeecskj.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gtjaocljzm.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.ehwqpu.com/Article/details/gtsdisicsd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.aibaodan.cn/Article/details/gtpyfxscod.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtkuvytacs.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cqqwz.cn/Article/details/gtkqvdrjwz.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.jyoumei.cn/Article/details/gtycaspcxk.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtfbmireaq.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.snrcjt.cn/Article/details/gtobboygne.html

[F12] CSV 读写
来源：http://dali.jqgfzy.top/Article/details/gtfhjwtpqh.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.tianlin.xyz/Article/details/gtqajlgyya.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhongyouzk.top/Article/details/gtinasulyl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jlsjyb.cn/Article/details/gtztdttfgs.html

TS:   // 同上
来源：http://dali.smart0.xyz/Article/details/gtlpgjmqwp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.daxiang520.top/Article/details/gtnqzytlhw.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.cucudq.cn/Article/details/gtqdlcidgs.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.c1oappe.top/Article/details/gtrhoezbeh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pengpengdd.cyou/Article/details/gtkyukzfft.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtxldflunw.html

G. 面向对象
来源：http://dali.jyoumei.cn/Article/details/gtgxcxdlxw.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtdoecjxvz.html

[G01] 定义类
来源：http://dali.cqqwz.cn/Article/details/gtiozzswyb.html

Py:   class User: pass
来源：http://dali.tian-w.cn/Article/details/gtverhunyo.html

PHP:  class User {}
来源：http://dali.hnqzz.top/Article/details/gtdcwhquap.html

JS:   class User {}
来源：http://dali.smart0.xyz/Article/details/gtaynmcoba.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtnqkgzvug.html

Java: class User {}
来源：http://dali.sufxvd.cn/Article/details/gtlereblrf.html

Go:   type User struct { Name string }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtjfurvl.html

Ruby: class User; end
来源：http://dali.chenzaomai.com/Article/details/gtyplvxjmq.html

C#:   class User {}
来源：http://dali.jyoumei.cn/Article/details/gtlhodukcl.html

[G02] 构造函数
来源：http://dali.hysaishi.cn/Article/details/gtkwunpfjy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jyoumei.cn/Article/details/gtxrgofkzk.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.sweek.top/Article/details/gtyhpsjgoq.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtbljvszqu.html

TS:   constructor(public name: string) {}
来源：http://dali.daria6918.cn/Article/details/gtqydgaewa.html

Java: User(String name) { this.name = name; }
来源：http://dali.nwbrower.top/Article/details/gtkfrkjoqa.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gtaflvhymx.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqlgjvlh.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnazhjfxq.html

[G03] 实例属性
来源：http://dali.yuxming.cn/Article/details/gtnroidczc.html

Py:   self.name = "x"
来源：http://dali.tanke756.top/Article/details/gtmevgcqsh.html

PHP:  public string $name = "x";
来源：http://dali.iojbl.cn/Article/details/gtjyrppgnt.html

JS:   this.name = "x";
来源：http://dali.xuetiantiany.cn/Article/details/gtjjhvbdpv.html

TS:   name: string = "x";
来源：http://dali.0kj1m.cn/Article/details/gtfshywtnr.html

Java: private String name;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcubhejlr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.redwolf501.top/Article/details/gtzbedakew.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtyjydsddw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tian-w.cn/Article/details/gtcxfzdrrh.html

[G04] 定义方法
来源：http://dali.gzhubu.top/Article/details/gtkkwmwltu.html

Py:   def greet(self): return self.name
来源：http://dali.shanyushiyangtech.top/Article/details/gtxyeogios.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.c1oappe.top/Article/details/gtshertpji.html

JS:   greet() { return this.name; }
来源：http://dali.yanxiufei.cn/Article/details/gtvnfitfft.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtnsgxmimq.html

Java: String greet() { return name; }
来源：http://dali.yangfankeji.com/Article/details/gtpaeixbjm.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jianghu66.top/Article/details/gtzgwgijls.html

Ruby: def greet; @name; end
来源：http://dali.fzhhl.top/Article/details/gttwbfxwyz.html

C#:   public string Greet() => Name;
来源：http://dali.guowangkeji.top/Article/details/gterpmjayv.html

[G05] 继承
来源：http://dali.xuetiantiany.cn/Article/details/gtkdlqksvn.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gtirwutjym.html

PHP:  class Admin extends User {}
来源：http://dali.hysaishi.cn/Article/details/gtikypvfxr.html

JS:   class Admin extends User {}
来源：http://dali.jinghuilouyu.cn/Article/details/gthceqygzz.html

TS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gtlcodalno.html

Java: class Admin extends User {}
来源：http://dali.cheryme.top/Article/details/gtqhrianmx.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.xuanzx.com/Article/details/gtzxlwphgi.html

Ruby: class Admin < User; end
来源：http://dali.zdqjudy.top/Article/details/gttpwlcfjs.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gtpqxlvgyu.html

[G06] 重写方法
来源：http://dali.yangfankeji.com/Article/details/gtfknckcgv.html

Py:   def greet(self): return "admin"
来源：http://dali.dianchejie.cn/Article/details/gtuykanpwg.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuanzx.com/Article/details/gtwnhzuhyc.html

JS:   greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gteaomnjbl.html

TS:   greet(): string { return "admin"; }
来源：http://dali.jqgufenzy.top/Article/details/gtrtqxffqz.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gtyetlcwdb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yangfankeji.com/Article/details/gtthucewtx.html

Ruby: def greet; "admin"; end
来源：http://dali.feifeiyinyue.top/Article/details/gtkgtljevl.html

C#:   public override string Greet() => "admin";
来源：http://dali.gogol.net.cn/Article/details/gtrarzshkp.html

[G07] 调用父类方法
来源：http://dali.yonumen.top/Article/details/gtssbyyzhu.html

Py:   super().greet()
来源：http://dali.meibo888.top/Article/details/gtkgokhkae.html

PHP:  parent::greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtziidahuf.html

JS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gtcxuqdfhv.html

TS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtzupxsttx.html

Java: super.greet();
来源：http://dali.ybcxt.top/Article/details/gtxsbwvunk.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zycfv.cn/Article/details/gtabgwmbwe.html

Ruby: super
来源：http://dali.dashuyun.cn/Article/details/gtqtqrqcpi.html

C#:   base.Greet();
来源：http://dali.hnqzz.top/Article/details/gtexilepst.html

[G08] 静态方法与属性
来源：http://dali.feifeiyinyue.top/Article/details/gtxyvllsas.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcprhtdjq.html

PHP:  public static function f() {}
来源：http://dali.yvedp.cn/Article/details/gtkgqnscef.html

JS:   static f() {}
来源：http://dali.haohaochexian.top/Article/details/gturcvwjwq.html

TS:   static f(): void {}
来源：http://dali.xuetiantiany.cn/Article/details/gtjitlxmru.html

Java: static void f() {}
来源：http://dali.sxryk.cn/Article/details/gtpjvhxive.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.hywenlv.cn/Article/details/gtbkbxqjfl.html

Ruby: def self.f; end
来源：http://dali.hysaishi.cn/Article/details/gtebdzqxwt.html

C#:   public static void F() {}
来源：http://dali.ybcxt.top/Article/details/gtfiseacau.html

[G09] 接口 / 抽象类
来源：http://dali.smart0.xyz/Article/details/gtwljvtshk.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.daria6918.cn/Article/details/gtilapfczj.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.xuanzx.com/Article/details/gtotwznuyh.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.pengpengdd.cyou/Article/details/gtpnppwszh.html

TS:   interface Shape { area(): number; }
来源：http://dali.haohaochexian.top/Article/details/gtdgiilboz.html

Java: interface Shape { double area(); }
来源：http://dali.gaohongyu789.top/Article/details/gtljiwhngb.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.zhiwuduotai.top/Article/details/gtbcfbduzw.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.jlsjyb.cn/Article/details/gtwajchcem.html

C#:   interface IShape { double Area(); }
来源：http://dali.cucudq.cn/Article/details/gtjxjumicq.html

[G10] 访问控制
来源：http://dali.smart0.xyz/Article/details/gtldyssvtg.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.tanke756.top/Article/details/gtfcfjdrem.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gtkrhcyxff.html

JS:   #private 字段；其余公开
来源：http://dali.fzhhl.top/Article/details/gtmxlfkvle.html

TS:   public / protected / private
来源：http://dali.cheryme.top/Article/details/gtzpgfdhle.html

Java: public / protected / private / 默认包级
来源：http://dali.meibo888.top/Article/details/gtyaniwseg.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yj20258888.top/Article/details/gthkcwkxjp.html

Ruby: public / protected / private
来源：http://dali.zhongyouzk.top/Article/details/gtwxezpoma.html

C#:   public / protected / private / internal
来源：http://dali.yanxiufei.cn/Article/details/gtcxmyivkq.html

[G11] getter / setter
来源：http://dali.aizwys.cn/Article/details/gtvdsewoto.html

Py:   @property 与 @x.setter
来源：http://dali.dianchejie.cn/Article/details/gtzjsydccs.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.quarkkingdee.top/Article/details/gtzuxiepsw.html

JS:   get name() { return this._name; }
来源：http://dali.redwolf501.top/Article/details/gttcycnbui.html

TS:   get name(): string { return this._name; }
来源：http://dali.haohaochexian.top/Article/details/gtsgxmgseh.html

Java: public String getName() { return name; }
来源：http://dali.cheryme.top/Article/details/gtjncykqsf.html

Go:   func (u User) GetName() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gteilswryb.html

Ruby: attr_accessor :name
来源：http://dali.meibo888.top/Article/details/gtxbrdewyi.html

C#:   public string Name { get; set; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjenwmiki.html

[G12] 对象转字符串
来源：http://dali.zycfv.cn/Article/details/gtmfyofara.html

Py:   def __str__(self): return self.name
来源：http://dali.wangshuangyany.cn/Article/details/gtjzlmfdsr.html


<!-- 参考信息 -->