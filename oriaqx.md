代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gterlyipeq.html

Ruby: s.count("a")
来源：http://dali.guannengcc.top/Article/details/gttucvngar.html

C#:   s.Count(c => c == 'a')
来源：http://dali.yuanzhike.top/Article/details/gtdfdsjwzj.html

[E13] 逐字符遍历
来源：http://dali.jyoumei.cn/Article/details/gthsxgevzq.html

Py:   for ch in s: print(ch)
来源：http://dali.yangfankeji.com/Article/details/gtuceamitz.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.cdnleiting.top/Article/details/gtvnrenxhs.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.dianchejie.cn/Article/details/gtsosocbrl.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.xuetiantiany.cn/Article/details/gtyilxshwp.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yvedp.cn/Article/details/gtjnesnhud.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jiagoushi.top/Article/details/gtifsgeacb.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yangfankeji.com/Article/details/gtfnfzsnxv.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.nanxinkj.top/Article/details/gthvpptmme.html

[E14] URL 编码与 Base64
来源：http://dali.jqgfzy.top/Article/details/gtmnmhtkwj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.c1oappe.top/Article/details/gttxgginch.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.nanxuanxn.top/Article/details/gtrdafbyvn.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.sxryk.cn/Article/details/gttvxbyjto.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.cashguo.top/Article/details/gtxrhrftau.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.shzxlz.cn/Article/details/gtyoyjbxpu.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinqigfzy.top/Article/details/gtnafacpzj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxuanxn.top/Article/details/gthwpjsyzz.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezghixga.html

[E15] HTML 转义 / 反转义
来源：http://dali.jinqigfzy.top/Article/details/gtkwhrskum.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yongpay.top/Article/details/gtqkzdczfi.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.meibo888.top/Article/details/gtssyubjxb.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.yvedp.cn/Article/details/gtbkrmgpsg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.c1oappe.top/Article/details/gttkofakcm.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xuanzx.com/Article/details/gtmqenopbm.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.nwbrower.top/Article/details/gttkjmnysd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtapyaanjt.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnxiangtu.top/Article/details/gtoiimgafq.html

[E16] 数字千分位
来源：http://dali.jqgfzy.top/Article/details/gtyooiaqow.html

Py:   f"{1234567:,}"
来源：http://dali.c1oappe.top/Article/details/gthvpikoyb.html

PHP:  number_format(1234567);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbnfiaavd.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.quarkkingdee.top/Article/details/gtyhaigdof.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtelhnmjtb.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.havefunace.top/Article/details/gtrxgkabqe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tanke756.top/Article/details/gtxszzjlmk.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.vqdsnc.cn/Article/details/gtsbebgcwd.html

C#:   1234567.ToString("N0")
来源：http://dali.mhx1999.top/Article/details/gtsgtcgsdh.html

[E17] 首字母大写
来源：http://dali.svipenyu.cn/Article/details/gtwcedjpdt.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.gotoacloud.top/Article/details/gtfscyugnx.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.jyoumei.cn/Article/details/gtpgawjvpw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.sxryk.cn/Article/details/gtmyozyaeq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.ybcxt.top/Article/details/gtncxbcycj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtkhxvltzd.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hnqzz.top/Article/details/gteufcnbjj.html

Ruby: s.capitalize
来源：http://dali.hnqzz.top/Article/details/gtmiaqqxnn.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.redwolf501.top/Article/details/gtxoxkksvk.html

[E18] 模板占位符替换
来源：http://dali.guannengcc.top/Article/details/gtprtdbtsr.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.svipenyu.cn/Article/details/gtadjjyzzg.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.bjfxy.top/Article/details/gtoclmmobk.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.hammf.cn/Article/details/gtczqjyhhj.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yongpay.top/Article/details/gteiceeeyq.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jianghu66.top/Article/details/gtzhuzkizm.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.svipenyu.cn/Article/details/gtbfolpxmz.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guowangkeji.top/Article/details/gtshompecj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jyoumei.cn/Article/details/gtcqkggcdh.html

[E19] 多行文本按行拆分
来源：http://dali.shangyingyoupin.top/Article/details/gthfkponoo.html

Py:   s.splitlines()
来源：http://dali.xinyue.icu/Article/details/gtdgpnuidb.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gtbbkiemxx.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gtwscfvdzu.html

TS:   s.split(/\r?\n/)
来源：http://dali.xziqi.cn/Article/details/gtfoadaddb.html

Java: s.lines().toList()
来源：http://dali.quarkkingdee.top/Article/details/gtgjpcgiaf.html

Go:   strings.Split(s, "\n")
来源：http://dali.snrcjt.cn/Article/details/gtorpadzot.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtzisjnrzg.html

C#:   s.Split('\n')
来源：http://dali.9152youxi.cn/Article/details/gtmfqvrsqk.html

[E20] 判断字符串是否为空
来源：http://dali.shanyushiyangkeji.top/Article/details/gtblicaove.html

Py:   if not s:
来源：http://dali.zhixingplan.top/Article/details/gttuwoezcm.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.jianghu66.top/Article/details/gtedlenbxg.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtmzcawjjn.html

TS:   if (s === "") {}
来源：http://dali.yuxming.cn/Article/details/gteharaqrn.html

Java: if (s.isEmpty()) {}
来源：http://dali.cheryme.top/Article/details/gtgtmitwty.html

Go:   if s == "" {}
来源：http://dali.sysykeji.top/Article/details/gtofnsvjbu.html

Ruby: if s.empty?
来源：http://dali.zhongyouzk.top/Article/details/gtkmvghcjw.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jlsjyb.cn/Article/details/gtbzqvqwmw.html

[E21] 超长截断加省略号
来源：http://dali.gotoacloud.top/Article/details/gthnijoxze.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.jqgfzy.top/Article/details/gtehkvgipi.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.ivvv.top/Article/details/gtcfuttbqu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gtvchopzhs.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtvpgtjqpu.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gtglgxfobr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhijiandao.cn/Article/details/gtaplyjbcl.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.dashuyun.cn/Article/details/gttosjxzfj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbtkdxfhj.html

[E22] 字节长度与字符长度
来源：http://dali.jlsjyb.cn/Article/details/gtaqkkyvvh.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtxshxtvwd.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zhijiandao.cn/Article/details/gtopergygc.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.zhengqikj.top/Article/details/gtgurpxjro.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gaohongyu789.top/Article/details/gtqacgkssj.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guowangkeji.top/Article/details/gtqbidyfhw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.zhiwuduotai.top/Article/details/gtwyrregro.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtxvhfrtxt.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinqigufen.top/Article/details/gttvmoodnz.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtpowadcgt.html

F. 文件与目录
来源：http://dali.nwbrower.top/Article/details/gtnzmduipv.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtzmmibhmt.html

[F01] 读取整个文件
来源：http://dali.havefunace.top/Article/details/gtdxmuandb.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinghuilouyu.cn/Article/details/gttfvdsncq.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jyoumei.cn/Article/details/gtceomvcsf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.ydzc1.top/Article/details/gteddvxyaj.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtbpucjspf.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.mhx1999.top/Article/details/gtixmzibgl.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cdnleiting.top/Article/details/gtpvcvlcgc.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtyaaofqgd.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.9152youxi.cn/Article/details/gtolzuhaij.html

[F02] 逐行读取文件
来源：http://dali.quarkkingdee.top/Article/details/gtqmkgppux.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hfpthk.cn/Article/details/gtsuixcjmj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgleuzogu.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.xuanzx.com/Article/details/gtqhkltasj.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yj202588.top/Article/details/gtortmytvl.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.fengsongda.top/Article/details/gtfnyaxbdw.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.0kj1m.cn/Article/details/gtrrkamqbo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.havefunace.top/Article/details/gtjrtjlsrr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jiagoushi.top/Article/details/gtaklvoscm.html

[F03] 写入文件（覆盖）
来源：http://dali.hfpthk.cn/Article/details/gthvwkzuiq.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.snrcjt.cn/Article/details/gtmvsrdwph.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.chenzaomai.com/Article/details/gtnvbcaovf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shangyingyoupin.top/Article/details/gtbxajxhax.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.bjfxy.top/Article/details/gtnejjazyp.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.ydzc1.top/Article/details/gticnulamx.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jqgufenzy.top/Article/details/gtbzaxbzpz.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgufenzy.top/Article/details/gtjnbncpdb.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hywenlv.cn/Article/details/gtqpnyjqkd.html

[F04] 追加写入文件
来源：http://dali.ydzc1.top/Article/details/gtevyrofwa.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gtfwnslzhp.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkybjfbwq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.c1oappe.top/Article/details/gthqwhaygb.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hnqzz.top/Article/details/gtbpitflze.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.yuxming.cn/Article/details/gtwqdmrkwb.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gteaqxhkmy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtwsggbgzg.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gtfnojtstr.html

[F05] 判断文件或目录是否存在
来源：http://dali.sufxvd.cn/Article/details/gtvdbidqjp.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ppjwa.cn/Article/details/gtabmwjbfd.html

PHP:  file_exists("a.txt");
来源：http://dali.yj20258888.top/Article/details/gttwwamnay.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sufxvd.cn/Article/details/gthrczoktd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tian-w.cn/Article/details/gtcvttvhaa.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.ybcxt.top/Article/details/gtpkaunuut.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.ivvv.top/Article/details/gtbvnvbzbw.html

Ruby: File.exist?("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtvbjcfeoq.html

C#:   File.Exists("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtukqthqrq.html

[F06] 删除文件
来源：http://dali.0kj1m.cn/Article/details/gttqlmhtun.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtsmwxqpuk.html

PHP:  unlink("a.txt");
来源：http://dali.0kj1m.cn/Article/details/gtqsimbtkl.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtivgxlbsj.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zdqjudy.top/Article/details/gtqcgvqugj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtatgvcyep.html

Go:   os.Remove("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtygowjtut.html

Ruby: File.delete("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtyrxnwjds.html

C#:   File.Delete("a.txt");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtremprsfg.html

[F07] 创建目录（含多级）
来源：http://dali.yueranfly.top/Article/details/gtixhzvqjn.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.sufxvd.cn/Article/details/gtrsysumda.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.chenzaomai.com/Article/details/gtwaqmoavq.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.quarkkingdee.top/Article/details/gtfrgfvyyk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yuanzhike.top/Article/details/gtrfgwslss.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.chenlongwang.top/Article/details/gtyhulzavc.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yj202588.top/Article/details/gtxwyaiunb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.xinyue.icu/Article/details/gtkuhetdub.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.havefunace.top/Article/details/gttotyhfko.html

[F08] 遍历目录
来源：http://dali.gzhubu.top/Article/details/gtvrjnpsek.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.shanyushiyangtech.top/Article/details/gtskuqeqyu.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cucudq.cn/Article/details/gtydqafzrq.html

JS:   fs.readdirSync("dir")
来源：http://dali.feifeiyinyue.top/Article/details/gtzwvzwcfi.html

TS:   fs.readdirSync("dir")
来源：http://dali.jyoumei.cn/Article/details/gtsvrbpjzj.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.guannengcc.top/Article/details/gtdwnkvoki.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.mhx1999.top/Article/details/gtezathncb.html

Ruby: Dir.children("dir")
来源：http://dali.c1oappe.top/Article/details/gtxdlgujfa.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yj20258.top/Article/details/gttdxdfjdq.html

[F09] 获取文件大小
来源：http://dali.quarkkingdee.top/Article/details/gtmpwqrcxw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtocxsmvqo.html

PHP:  filesize("a.txt");
来源：http://dali.shangyingyoupin.top/Article/details/gtcbtfxyju.html

JS:   fs.statSync("a.txt").size
来源：http://dali.jiagoushi.top/Article/details/gtwcfcytox.html

TS:   fs.statSync("a.txt").size
来源：http://dali.hfpthk.cn/Article/details/gtoigvelxe.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.sxryk.cn/Article/details/gtotvmzweg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.shangyingyoupin.top/Article/details/gtlzedglfk.html

Ruby: File.size("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gtvcrddyip.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yvedp.cn/Article/details/gtpcinjpvv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.zhoulong.xyz/Article/details/gtfczjbjff.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtvrmoljdc.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.gogol.net.cn/Article/details/gthgkipsgf.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtidlywdbp.html

TS:   path.extname("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtwxczrtgj.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yuxming.cn/Article/details/gtwakrekht.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cdnleiting.top/Article/details/gteghpcaks.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gtkycvfyjc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.iojbl.cn/Article/details/gtgxuvnexh.html

[F11] 复制与移动文件
来源：http://dali.wangdashe.top/Article/details/gtcpsrudou.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.sweek.top/Article/details/gtzmfibimz.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.mhx1999.top/Article/details/gtuofrchcm.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jiagoushi.top/Article/details/gtctutfbay.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jyoumei.cn/Article/details/gtybjvuqqn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.yj20258888.top/Article/details/gtksqtkrwn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.aizwys.cn/Article/details/gtfzhfugkw.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.cheryme.top/Article/details/gtrcqiajgd.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.zhoulong.xyz/Article/details/gtdqmtzzqj.html

[F12] CSV 读写
来源：http://dali.fzhhl.top/Article/details/gtlnshidgk.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.vqdsnc.cn/Article/details/gtqgdcqrpf.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxcpjzcu.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jianghu66.top/Article/details/gtvzjxqogw.html

TS:   // 同上
来源：http://dali.vqdsnc.cn/Article/details/gtgaqcbnxg.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jqgfzy.top/Article/details/gtspqmqgdu.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.jlsjyb.cn/Article/details/gteyvwfacm.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.meibo888.top/Article/details/gtivpijnso.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinghuilouyu.cn/Article/details/gtaunyaajt.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtngcbnokw.html

G. 面向对象
来源：http://dali.jiagoushi.top/Article/details/gtxglixzxc.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlhsmvcrg.html

[G01] 定义类
来源：http://dali.hnqzz.top/Article/details/gtnhzyecbd.html

Py:   class User: pass
来源：http://dali.sufxvd.cn/Article/details/gtlwzpzpdo.html

PHP:  class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gttglgslth.html

JS:   class User {}
来源：http://dali.xziqi.cn/Article/details/gtasauapvw.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gtetjqdbah.html

Java: class User {}
来源：http://dali.shuidangran.top/Article/details/gtlehnopto.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtrtuqgyee.html

Ruby: class User; end
来源：http://dali.zhixingplan.top/Article/details/gttzcebcyo.html

C#:   class User {}
来源：http://dali.tian-w.cn/Article/details/gtgsonxzun.html

[G02] 构造函数
来源：http://dali.shangyingyoupin.top/Article/details/gtxvnjmavn.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.birdmap.top/Article/details/gtfwqmurgx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.hfpthk.cn/Article/details/gthrchduqd.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.yueranfly.top/Article/details/gtbpcumfiz.html

TS:   constructor(public name: string) {}
来源：http://dali.gaohongyu789.top/Article/details/gtreqpfeky.html

Java: User(String name) { this.name = name; }
来源：http://dali.jlsjyb.cn/Article/details/gtmhyyvpbo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.zhoulong.xyz/Article/details/gtzhudmvny.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.shzxlz.cn/Article/details/gtrgzkmaso.html

C#:   public User(string name) { Name = name; }
来源：http://dali.zhixingplan.top/Article/details/gteilpdhiu.html

[G03] 实例属性
来源：http://dali.ehwqpu.com/Article/details/gtxehbnjqs.html

Py:   self.name = "x"
来源：http://dali.gaohongyu789.top/Article/details/gtsgprcmyn.html

PHP:  public string $name = "x";
来源：http://dali.guowangkeji.top/Article/details/gtpnozfhqi.html

JS:   this.name = "x";
来源：http://dali.yj202588.top/Article/details/gtbpalogor.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtgzzbnygr.html

Java: private String name;
来源：http://dali.haohaochexian.top/Article/details/gtkggtuiej.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.chenzaomai.com/Article/details/gtpcqmofxq.html

Ruby: @name = "x"
来源：http://dali.zhixingplan.top/Article/details/gtbzladfud.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nwbrower.top/Article/details/gtkhewzsuv.html

[G04] 定义方法
来源：http://dali.quarkkingdee.top/Article/details/gtxvrhpzpm.html

Py:   def greet(self): return self.name
来源：http://dali.feifeiyinyue.top/Article/details/gtjjsttpvo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.sysykeji.top/Article/details/gteivqaziz.html

JS:   greet() { return this.name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddkthgsi.html

TS:   greet(): string { return this.name; }
来源：http://dali.jinqigufen.top/Article/details/gtazouwvsv.html

Java: String greet() { return name; }
来源：http://dali.ydzc1.top/Article/details/gtuhuhntjx.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gtpktzyutz.html

Ruby: def greet; @name; end
来源：http://dali.zhongyouzk.top/Article/details/gtcqajahni.html

C#:   public string Greet() => Name;
来源：http://dali.kuanghao11.cn/Article/details/gtslmuqyry.html

[G05] 继承
来源：http://dali.mhx1999.top/Article/details/gtikwjujdn.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtrtchbual.html

PHP:  class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gthvkgteym.html

JS:   class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gthltapguh.html

TS:   class Admin extends User {}
来源：http://dali.jyoumei.cn/Article/details/gtmemjmhaq.html

Java: class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gtmmfzksok.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqbnigzm.html

Ruby: class Admin < User; end
来源：http://dali.nanxinkj.top/Article/details/gtddbktiog.html

C#:   class Admin : User {}
来源：http://dali.jlsjyb.cn/Article/details/gtqmvphvkl.html

[G06] 重写方法
来源：http://dali.aibaodan.cn/Article/details/gthaozybdm.html

Py:   def greet(self): return "admin"
来源：http://dali.yj202588.top/Article/details/gtdungrncx.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.tian-w.cn/Article/details/gtsokgxikd.html

JS:   greet() { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtjgmtayjf.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtogfzkaqt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gtlnjbsrzj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.shuidangran.top/Article/details/gtbhgeqbcq.html

Ruby: def greet; "admin"; end
来源：http://dali.fengsongda.top/Article/details/gtnoipkruz.html

C#:   public override string Greet() => "admin";
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgfpwvlt.html

[G07] 调用父类方法
来源：http://dali.andypj.xyz/Article/details/gtuzjnmctq.html

Py:   super().greet()
来源：http://dali.havefunace.top/Article/details/gttkgcfgwi.html

PHP:  parent::greet();
来源：http://dali.xylfe.cn/Article/details/gtsuoymuav.html

JS:   super.greet();
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzycqxyab.html

TS:   super.greet();
来源：http://dali.tanke756.top/Article/details/gtgfcjghdl.html

Java: super.greet();
来源：http://dali.tian-w.cn/Article/details/gtzinhdxcn.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.yuanzhike.top/Article/details/gtnhtqdmiw.html

Ruby: super
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjgsxvxwb.html

C#:   base.Greet();
来源：http://dali.feifeiyinyue.top/Article/details/gtdlalgenq.html

[G08] 静态方法与属性
来源：http://dali.jinqigufen.top/Article/details/gtpjobssgr.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.hongshengwenyu.top/Article/details/gtuuklbqzf.html

PHP:  public static function f() {}
来源：http://dali.ybcxt.top/Article/details/gthpsrxpqo.html

JS:   static f() {}
来源：http://dali.wangdashe.top/Article/details/gtsvjqubwj.html

TS:   static f(): void {}
来源：http://dali.jinqigufen.top/Article/details/gtefueoodb.html

Java: static void f() {}
来源：http://dali.jlsjyb.cn/Article/details/gtqawswsey.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yj202588.top/Article/details/gtcutmswis.html

Ruby: def self.f; end
来源：http://dali.tian-w.cn/Article/details/gtenbitlgf.html

C#:   public static void F() {}
来源：http://dali.meibo888.top/Article/details/gtvnldvadu.html

[G09] 接口 / 抽象类
来源：http://dali.jqgufenzy.top/Article/details/gtfwosbtsy.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.chenjidiqi.icu/Article/details/gtkhunlfrg.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.0kj1m.cn/Article/details/gtgpxifkkc.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.yuanzhike.top/Article/details/gtdmedlfdm.html

TS:   interface Shape { area(): number; }
来源：http://dali.yonumen.top/Article/details/gtfbjscudr.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gtwawkhxns.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.c1oappe.top/Article/details/gtxfhyuvvs.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnrpodajw.html

C#:   interface IShape { double Area(); }
来源：http://dali.zycfv.cn/Article/details/gtlsgliplu.html

[G10] 访问控制
来源：http://dali.guowangkeji.top/Article/details/gtmmyphxdf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.aibaodan.cn/Article/details/gtihsztqru.html

PHP:  public / protected / private
来源：http://dali.xuanzx.com/Article/details/gtqrrhvhyv.html

JS:   #private 字段；其余公开
来源：http://dali.jianghu66.top/Article/details/gtpmkyirny.html

TS:   public / protected / private
来源：http://dali.cdnleiting.top/Article/details/gtboimimel.html

Java: public / protected / private / 默认包级
来源：http://dali.dianchejie.cn/Article/details/gtnuavwmba.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.yueranfly.top/Article/details/gttnyltjye.html

Ruby: public / protected / private
来源：http://dali.guowangkeji.top/Article/details/gtajwufzxb.html

C#:   public / protected / private / internal
来源：http://dali.pengpengdd.cyou/Article/details/gtypoiherj.html

[G11] getter / setter
来源：http://dali.cheryme.top/Article/details/gtcaoymepi.html

Py:   @property 与 @x.setter
来源：http://dali.hammf.cn/Article/details/gtrcztinid.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.jqgufenzy.top/Article/details/gtjwqwfphi.html


<!-- 参考信息 -->