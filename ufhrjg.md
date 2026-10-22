代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.zhengqikj.top/Article/details/gthyoralel.html

TS:   [...s].reverse().join("")
来源：http://dali.yonumen.top/Article/details/gtsqcgwlgc.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtjqahkcjj.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.cucudq.cn/Article/details/gtaaasxfhc.html

Ruby: s.reverse
来源：http://dali.shzxlz.cn/Article/details/gtaplzoweo.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.pengpengdd.cyou/Article/details/gtooyozbow.html

[E12] 统计某字符出现次数
来源：http://dali.zhoulong.xyz/Article/details/gttrwyuxbc.html

Py:   s.count("a")
来源：http://dali.chenlongwang.top/Article/details/gtghmbutso.html

PHP:  substr_count($s, "a");
来源：http://dali.cdnleiting.top/Article/details/gtymvfojdd.html

JS:   s.split("a").length - 1
来源：http://dali.gaohongyu789.top/Article/details/gttoexpaky.html

TS:   s.split("a").length - 1
来源：http://dali.jinqigufen.top/Article/details/gtwnrnbovh.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yj20258888.top/Article/details/gtfvjoxbhu.html

Go:   strings.Count(s, "a")
来源：http://dali.aibaodan.cn/Article/details/gtrkezjfkk.html

Ruby: s.count("a")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbltxmbul.html

C#:   s.Count(c => c == 'a')
来源：http://dali.shuidangran.top/Article/details/gtwsywvqos.html

[E13] 逐字符遍历
来源：http://dali.tianlin.xyz/Article/details/gtqqdqbvmg.html

Py:   for ch in s: print(ch)
来源：http://dali.yuanzhike.top/Article/details/gtmxbeynqo.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.tianlin.xyz/Article/details/gttsntqnen.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfvpowii.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.yongpay.top/Article/details/gtmheitcfj.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ybcxt.top/Article/details/gtunbzrqql.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.hnxiangtu.top/Article/details/gttqnhnuri.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzrurjyga.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.daria6918.cn/Article/details/gtjuqsiwom.html

[E14] URL 编码与 Base64
来源：http://dali.jyoumei.cn/Article/details/gtvjfcasqr.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhiwuduotai.top/Article/details/gtkcqytjkm.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.pycfn.com/Article/details/gtzupeierl.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sufxvd.cn/Article/details/gtnlklagvp.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.iojbl.cn/Article/details/gtsjchezge.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hfpthk.cn/Article/details/gtdnzhxdxu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.fzhhl.top/Article/details/gtulgvamsh.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.fzhhl.top/Article/details/gtsjgqhbwc.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.bjfxy.top/Article/details/gtdvqmvjyg.html

[E15] HTML 转义 / 反转义
来源：http://dali.ybcxt.top/Article/details/gtfdmcyuzu.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gthcnngdkp.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.xziqi.cn/Article/details/gtlqwzdrin.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.jqgufenzy.top/Article/details/gtrzakshxe.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnlpjmszi.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.chenlongwang.top/Article/details/gtwoytczhw.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.0kj1m.cn/Article/details/gtlwusrsqx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gttowxwvzu.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.yongpay.top/Article/details/gtoujuwylc.html

[E16] 数字千分位
来源：http://dali.dashuyun.cn/Article/details/gtegcboneb.html

Py:   f"{1234567:,}"
来源：http://dali.andypj.xyz/Article/details/gtflspsswo.html

PHP:  number_format(1234567);
来源：http://dali.hammf.cn/Article/details/gtduufskbq.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhiwuduotai.top/Article/details/gtorhgsdmd.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.hysaishi.cn/Article/details/gtvxlormib.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yanxiufei.cn/Article/details/gtieovbiwd.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.hongshengwenyu.top/Article/details/gtxshvaapb.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jinghuilouyu.cn/Article/details/gttygozmzt.html

C#:   1234567.ToString("N0")
来源：http://dali.guowangkeji.top/Article/details/gtnuoglbhh.html

[E17] 首字母大写
来源：http://dali.gzhubu.top/Article/details/gtojftxknt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.jyoumei.cn/Article/details/gtzjrjznvk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.haohaochexian.top/Article/details/gtjxwuhlnm.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sysykeji.top/Article/details/gtmvorubhd.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daxiang520.top/Article/details/gtlmmyjvxv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yuanzhike.top/Article/details/gtrylolthw.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sxryk.cn/Article/details/gtolgfogyx.html

Ruby: s.capitalize
来源：http://dali.xuetiantiany.cn/Article/details/gtothprexx.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhiwuduotai.top/Article/details/gtcbtthvax.html

[E18] 模板占位符替换
来源：http://dali.zycfv.cn/Article/details/gtyzjhuogm.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.tianlin.xyz/Article/details/gtwbkgsgii.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.nanxuanxn.top/Article/details/gthzmrfowd.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gtdgoptpuo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.316326.xyz/Article/details/gtbuwyaocm.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gturljpmkw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.mhx1999.top/Article/details/gtnpadoryr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ydzc1.top/Article/details/gtehjwmxbq.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.snrcjt.cn/Article/details/gtyjwyyamn.html

[E19] 多行文本按行拆分
来源：http://dali.xinyue.icu/Article/details/gtjqyujikj.html

Py:   s.splitlines()
来源：http://dali.chenzaomai.com/Article/details/gtzolyhbny.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.hongshengwenyu.top/Article/details/gtvymihisj.html

JS:   s.split(/\r?\n/)
来源：http://dali.bjfxy.top/Article/details/gtfqjwkurh.html

TS:   s.split(/\r?\n/)
来源：http://dali.kuanghao11.cn/Article/details/gttvklpznj.html

Java: s.lines().toList()
来源：http://dali.daria6918.cn/Article/details/gtnawagfqb.html

Go:   strings.Split(s, "\n")
来源：http://dali.zhongyouzk.top/Article/details/gtuumuepjy.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtgxtkaazf.html

C#:   s.Split('\n')
来源：http://dali.jiagoushi.top/Article/details/gtkefuuwfq.html

[E20] 判断字符串是否为空
来源：http://dali.sufxvd.cn/Article/details/gtzoqheudh.html

Py:   if not s:
来源：http://dali.jianghu66.top/Article/details/gtctguenpl.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.chenjidiqi.icu/Article/details/gtklnngjnh.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.jianghu66.top/Article/details/gtxmnatgxt.html

TS:   if (s === "") {}
来源：http://dali.snrcjt.cn/Article/details/gthjrxdovj.html

Java: if (s.isEmpty()) {}
来源：http://dali.kuanghao11.cn/Article/details/gtvpslwnmh.html

Go:   if s == "" {}
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzuzghau.html

Ruby: if s.empty?
来源：http://dali.xinyue.icu/Article/details/gtssqedguo.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.dashuyun.cn/Article/details/gtwltepkdo.html

[E21] 超长截断加省略号
来源：http://dali.zhoulong.xyz/Article/details/gtqnuvnlpr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.dashuyun.cn/Article/details/gtcgwwtepk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gotoacloud.top/Article/details/gtpkuwboib.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhengqikj.top/Article/details/gtaxsnxpnz.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.gotoacloud.top/Article/details/gtvinkeive.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.hnxiangtu.top/Article/details/gtkefuvzuj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.andypj.xyz/Article/details/gtgakieiri.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gtedawcval.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.hongshengwenyu.top/Article/details/gtybpecgcr.html

[E22] 字节长度与字符长度
来源：http://dali.xuetiantiany.cn/Article/details/gtzrbboise.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gotoacloud.top/Article/details/gtohvfznww.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jinqigfzy.top/Article/details/gtovtpzwys.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shzxlz.cn/Article/details/gtqoqsupzo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.316326.xyz/Article/details/gtjgpnmhpn.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.dashuyun.cn/Article/details/gtoixkvodt.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoqxfuhhf.html

Ruby: s.bytesize;  s.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcxmaqdpx.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.mhx1999.top/Article/details/gtcwipngyd.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgesdukkl.html

F. 文件与目录
来源：http://dali.shuidangran.top/Article/details/gtufkfddgh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtzeiwpzsp.html

[F01] 读取整个文件
来源：http://dali.yueranfly.top/Article/details/gtgwnbynwi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xylfe.cn/Article/details/gtdipwnqir.html

PHP:  file_get_contents("a.txt");
来源：http://dali.aibaodan.cn/Article/details/gtkvreeygw.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hammf.cn/Article/details/gttubzoszj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.dianchejie.cn/Article/details/gtpzhbybjr.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gtbjllfxzi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.wangshuangyany.cn/Article/details/gtobejvtzk.html

Ruby: File.read("a.txt")
来源：http://dali.jqgfzy.top/Article/details/gtdypiztlc.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtvqvqtida.html

[F02] 逐行读取文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdyoqbwhx.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.gogol.net.cn/Article/details/gtotxvaxsw.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtuxfeqcei.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shzxlz.cn/Article/details/gtbmqfrqbn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhoulong.xyz/Article/details/gtcajajaiz.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.yangfankeji.com/Article/details/gtcsxnjcef.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hysaishi.cn/Article/details/gtoncsxvvz.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.shuidangran.top/Article/details/gtyvhezcsc.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.birdmap.top/Article/details/gtglumlxna.html

[F03] 写入文件（覆盖）
来源：http://dali.nwbrower.top/Article/details/gtwolpqjgq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.9152youxi.cn/Article/details/gtmnqujgwo.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.cqqwz.cn/Article/details/gtkxvgglan.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ybcxt.top/Article/details/gtcipjnpur.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangdashe.top/Article/details/gtrqsczcdz.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.snrcjt.cn/Article/details/gtpxouwzkq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ehwqpu.com/Article/details/gtrbuahsok.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.tanke756.top/Article/details/gtjoocxaez.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cheryme.top/Article/details/gtihvwnocs.html

[F04] 追加写入文件
来源：http://dali.daxiang520.top/Article/details/gtkdkeivpp.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shzxlz.cn/Article/details/gtggdnoxje.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.hongshengwenyu.top/Article/details/gtoweenjkf.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnxiangtu.top/Article/details/gtnkjwswmq.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gttpfmgbpl.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.mhx1999.top/Article/details/gtasiuoids.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtajczggzk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.feifeiyinyue.top/Article/details/gtjrmgmlnb.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.snrcjt.cn/Article/details/gtbrfxjmpk.html

[F05] 判断文件或目录是否存在
来源：http://dali.yangfankeji.com/Article/details/gtwxahyfdw.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.zhiwuduotai.top/Article/details/gtrfsppvhf.html

PHP:  file_exists("a.txt");
来源：http://dali.feifeiyinyue.top/Article/details/gtgchmfxsi.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xylfe.cn/Article/details/gtdsdavdls.html

TS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gttoxhwncg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtucjxuheg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cqqwz.cn/Article/details/gtfvkqhpeh.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gtwvciuuuk.html

C#:   File.Exists("a.txt")
来源：http://dali.dashuyun.cn/Article/details/gtgxvhppdq.html

[F06] 删除文件
来源：http://dali.yj202588.top/Article/details/gtuhcilgcm.html

Py:   os.remove("a.txt")
来源：http://dali.jinghuilouyu.cn/Article/details/gtbuabybik.html

PHP:  unlink("a.txt");
来源：http://dali.sweek.top/Article/details/gtfnretnaa.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gttyevyakh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gtjqfptetj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xuetiantiany.cn/Article/details/gtgoagqjdf.html

Go:   os.Remove("a.txt")
来源：http://dali.zhixingplan.top/Article/details/gtsrskxbdz.html

Ruby: File.delete("a.txt")
来源：http://dali.yongpay.top/Article/details/gtdcboskdk.html

C#:   File.Delete("a.txt");
来源：http://dali.sysykeji.top/Article/details/gtfgofuakt.html

[F07] 创建目录（含多级）
来源：http://dali.jinqigfzy.top/Article/details/gtkekrzvnf.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.xuanzx.com/Article/details/gtypgrmorg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yanxiufei.cn/Article/details/gtlbfvlnoc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtjfxmmvvu.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cdnleiting.top/Article/details/gtkbtodsin.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.hfpthk.cn/Article/details/gtbdcstmrr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yvedp.cn/Article/details/gtougfklkg.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.vqdsnc.cn/Article/details/gtpwwcvlwb.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.zhongyouzk.top/Article/details/gtorbbrvls.html

[F08] 遍历目录
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlejyaeat.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.gogol.net.cn/Article/details/gtliloavoa.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.yj202588.top/Article/details/gtylklwuhg.html

JS:   fs.readdirSync("dir")
来源：http://dali.zdqjudy.top/Article/details/gtwrpywobl.html

TS:   fs.readdirSync("dir")
来源：http://dali.sufxvd.cn/Article/details/gttafwybhf.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinqigufen.top/Article/details/gtgixmmnur.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtrkeyxuvm.html

Ruby: Dir.children("dir")
来源：http://dali.yuanzhike.top/Article/details/gtsxbedgpb.html

C#:   Directory.GetFiles("dir")
来源：http://dali.bjfxy.top/Article/details/gtulxcfqud.html

[F09] 获取文件大小
来源：http://dali.feifeiyinyue.top/Article/details/gtoepekdzw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ivvv.top/Article/details/gtiiesvfab.html

PHP:  filesize("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gtwybtqotp.html

JS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gtszrzekjp.html

TS:   fs.statSync("a.txt").size
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxxqdimd.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yuanzhike.top/Article/details/gtcedtevhz.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jyoumei.cn/Article/details/gtihzqalxp.html

Ruby: File.size("a.txt")
来源：http://dali.aizwys.cn/Article/details/gttkbyfnnf.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.cashguo.top/Article/details/gtuvgxkdnp.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.smart0.xyz/Article/details/gtihyiiund.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yongpay.top/Article/details/gtqlxprqqn.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtbbejarhf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtnxquhfba.html

TS:   path.extname("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtplvhlwcr.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gttcusklit.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gthxugowxn.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtcahnamst.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtnaoptiok.html

[F11] 复制与移动文件
来源：http://dali.cheryme.top/Article/details/gthwhiifmo.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.meibo888.top/Article/details/gttfnhpilx.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.snrcjt.cn/Article/details/gtaeofvtwr.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtyslkdzxg.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtvttggdjj.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj202588.top/Article/details/gtnsmkvomd.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.xuetiantiany.cn/Article/details/gtbkvluxdx.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtpsfqepgt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daria6918.cn/Article/details/gtusmwnrtd.html

[F12] CSV 读写
来源：http://dali.yuxming.cn/Article/details/gtjsapgbzm.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshvbybja.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.smart0.xyz/Article/details/gtjqzzobhe.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hnxiangtu.top/Article/details/gtdpcjruch.html

TS:   // 同上
来源：http://dali.guannengcc.top/Article/details/gtiwhfzdqp.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hfpthk.cn/Article/details/gtelftiwkm.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zycfv.cn/Article/details/gtvpaectvx.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.redwolf501.top/Article/details/gtougkvfkr.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhijiandao.cn/Article/details/gtpvvnhvvy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtlcdcjdyk.html

G. 面向对象
来源：http://dali.hnqzz.top/Article/details/gtjjlobyuz.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtjftjumpf.html

[G01] 定义类
来源：http://dali.aibaodan.cn/Article/details/gtbyvyiauj.html

Py:   class User: pass
来源：http://dali.xziqi.cn/Article/details/gtkdcvwkvc.html

PHP:  class User {}
来源：http://dali.aizwys.cn/Article/details/gtlggzhrto.html

JS:   class User {}
来源：http://dali.kuanghao11.cn/Article/details/gthpbutxpe.html

TS:   class User { name: string = ""; }
来源：http://dali.yj20258.top/Article/details/gtrufbjrjk.html

Java: class User {}
来源：http://dali.snrcjt.cn/Article/details/gtyeiunncw.html

Go:   type User struct { Name string }
来源：http://dali.hongshengwenyu.top/Article/details/gtzyblmmuh.html

Ruby: class User; end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvonxcpdp.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gtzxmbqygl.html

[G02] 构造函数
来源：http://dali.hammf.cn/Article/details/gtpojexywu.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinqigufen.top/Article/details/gtqfsfcskv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.yuxming.cn/Article/details/gtnsueymus.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gteqursmco.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gtxtqrqetw.html

Java: User(String name) { this.name = name; }
来源：http://dali.gotoacloud.top/Article/details/gtsbyysbda.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.jianghu66.top/Article/details/gtcxmtlbmp.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.meibo888.top/Article/details/gtthekjsyv.html

C#:   public User(string name) { Name = name; }
来源：http://dali.dashuyun.cn/Article/details/gtidmkjnbq.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtidyxnlvq.html

Py:   self.name = "x"
来源：http://dali.ybcxt.top/Article/details/gtiqjxespb.html

PHP:  public string $name = "x";
来源：http://dali.fzhhl.top/Article/details/gtflmktrxu.html

JS:   this.name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gtfvuxsioh.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gttmfhxdrb.html

Java: private String name;
来源：http://dali.zhengqikj.top/Article/details/gtvfplqwyb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.daxiang520.top/Article/details/gtbtrmisdw.html

Ruby: @name = "x"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcxwbugtd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.xziqi.cn/Article/details/gtpgbaoend.html

[G04] 定义方法
来源：http://dali.xylfe.cn/Article/details/gtqyawggdc.html

Py:   def greet(self): return self.name
来源：http://dali.sysykeji.top/Article/details/gteicqtdab.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.havefunace.top/Article/details/gthsucqsyl.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtlonwjgpj.html

TS:   greet(): string { return this.name; }
来源：http://dali.316326.xyz/Article/details/gtciqvdyyp.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtgtrzuxbt.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.zhiwuduotai.top/Article/details/gtjykjpapr.html

Ruby: def greet; @name; end
来源：http://dali.hammf.cn/Article/details/gtebvgryeu.html

C#:   public string Greet() => Name;
来源：http://dali.hysaishi.cn/Article/details/gtyuizzxua.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gtnoclbouw.html

Py:   class Admin(User): pass
来源：http://dali.yj20258.top/Article/details/gthtetrydf.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtlqylwbio.html

JS:   class Admin extends User {}
来源：http://dali.hammf.cn/Article/details/gthpkxbqrh.html

TS:   class Admin extends User {}
来源：http://dali.yj20258888.top/Article/details/gtsckmurnt.html

Java: class Admin extends User {}
来源：http://dali.meibo888.top/Article/details/gtwwrgdhey.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jlsjyb.cn/Article/details/gttpcwvthp.html

Ruby: class Admin < User; end
来源：http://dali.gogol.net.cn/Article/details/gtrtxausns.html

C#:   class Admin : User {}
来源：http://dali.wangshuangyany.cn/Article/details/gtcswaufpc.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtlrzitrkv.html

Py:   def greet(self): return "admin"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyhcdrmxn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlankvywt.html

JS:   greet() { return "admin"; }
来源：http://dali.birdmap.top/Article/details/gtnmmcijan.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtxolugjss.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtnftaipyo.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.hnqzz.top/Article/details/gttyyfwlac.html

Ruby: def greet; "admin"; end
来源：http://dali.fzhhl.top/Article/details/gtoqcjiobi.html

C#:   public override string Greet() => "admin";
来源：http://dali.cucudq.cn/Article/details/gtcvhqhbvq.html

[G07] 调用父类方法
来源：http://dali.mhx1999.top/Article/details/gtzmkslocu.html

Py:   super().greet()
来源：http://dali.redwolf501.top/Article/details/gtanljjbcs.html

PHP:  parent::greet();
来源：http://dali.jinqigufen.top/Article/details/gtfwhdtwey.html

JS:   super.greet();
来源：http://dali.xylfe.cn/Article/details/gtbzvtbgvh.html

TS:   super.greet();
来源：http://dali.cucudq.cn/Article/details/gtfpucvrkk.html

Java: super.greet();
来源：http://dali.pengpengdd.cyou/Article/details/gtbdkjkdzt.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.meibo888.top/Article/details/gtnipswlni.html

Ruby: super
来源：http://dali.meibo888.top/Article/details/gtcdoctucl.html

C#:   base.Greet();
来源：http://dali.zhoulong.xyz/Article/details/gtpnocyndv.html

[G08] 静态方法与属性
来源：http://dali.havefunace.top/Article/details/gtesvleqkk.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.wangdashe.top/Article/details/gtiuqsrsay.html

PHP:  public static function f() {}
来源：http://dali.yj20258.top/Article/details/gtposqiuka.html

JS:   static f() {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxpfdncjq.html

TS:   static f(): void {}
来源：http://dali.quarkkingdee.top/Article/details/gtpyzsgzhv.html

Java: static void f() {}
来源：http://dali.vqdsnc.cn/Article/details/gtdfdaeido.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yongpay.top/Article/details/gtpocyvocg.html

Ruby: def self.f; end
来源：http://dali.cheryme.top/Article/details/gtbtuidibl.html

C#:   public static void F() {}
来源：http://dali.zhijiandao.cn/Article/details/gtukkmcelf.html

[G09] 接口 / 抽象类
来源：http://dali.shuidangran.top/Article/details/gtllxfglyq.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ivvv.top/Article/details/gtgpllikdq.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.yvedp.cn/Article/details/gtuxoyksvp.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xziqi.cn/Article/details/gtlxvkzvcy.html

TS:   interface Shape { area(): number; }
来源：http://dali.fengsongda.top/Article/details/gtwtzphzvw.html

Java: interface Shape { double area(); }
来源：http://dali.chenzaomai.com/Article/details/gtwrilhwzc.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.xuetiantiany.cn/Article/details/gtijthkgkm.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhijiandao.cn/Article/details/gtbcbwbfju.html

C#:   interface IShape { double Area(); }
来源：http://dali.nanxinkj.top/Article/details/gtcrulzkzu.html


<!-- 参考信息 -->