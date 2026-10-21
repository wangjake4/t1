代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.yvedp.cn/Article/details/gtmgzuequg.html

Java: String.format("%03d", 7)
来源：http://dali.jyoumei.cn/Article/details/gtgsdprqig.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.tianlin.xyz/Article/details/gtctpjybgl.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.feifeiyinyue.top/Article/details/gtudaiynsb.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.sufxvd.cn/Article/details/gtlcptgwvc.html

[E11] 反转字符串
来源：http://dali.quarkkingdee.top/Article/details/gtiqmuydbb.html

Py:   s[::-1]
来源：http://dali.dashuyun.cn/Article/details/gtfikdvamd.html

PHP:  strrev($s);
来源：http://dali.vqdsnc.cn/Article/details/gtzcynksxn.html

JS:   [...s].reverse().join("")
来源：http://dali.tanke756.top/Article/details/gtwaentzrx.html

TS:   [...s].reverse().join("")
来源：http://dali.haohaochexian.top/Article/details/gtvwcciwcd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.guannengcc.top/Article/details/gtlyziyowl.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenjidiqi.icu/Article/details/gtohtozugw.html

Ruby: s.reverse
来源：http://dali.zhengqikj.top/Article/details/gtsuasrrxb.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.316326.xyz/Article/details/gtqwumflvy.html

[E12] 统计某字符出现次数
来源：http://dali.gzhubu.top/Article/details/gtobrfkonn.html

Py:   s.count("a")
来源：http://dali.ehwqpu.com/Article/details/gtdxqfucii.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigfzy.top/Article/details/gtpvrjhtfe.html

JS:   s.split("a").length - 1
来源：http://dali.sufxvd.cn/Article/details/gtwtntntcn.html

TS:   s.split("a").length - 1
来源：http://dali.smart0.xyz/Article/details/gtnvfjrwly.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jlsjyb.cn/Article/details/gtxdszhvox.html

Go:   strings.Count(s, "a")
来源：http://dali.shangyingyoupin.top/Article/details/gteyuvnwcv.html

Ruby: s.count("a")
来源：http://dali.yj20258888.top/Article/details/gtdqgxpaez.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gogol.net.cn/Article/details/gtwhjbhmqr.html

[E13] 逐字符遍历
来源：http://dali.yvedp.cn/Article/details/gtgdvlazhc.html

Py:   for ch in s: print(ch)
来源：http://dali.wangdashe.top/Article/details/gtrmagbxso.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.zhoulong.xyz/Article/details/gtimtejtnc.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtuecnhwyw.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.wangdashe.top/Article/details/gtbczycozn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yonumen.top/Article/details/gtoejankeo.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtdoxmfwhd.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.yvedp.cn/Article/details/gtafdemrjn.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtersdepqk.html

[E14] URL 编码与 Base64
来源：http://dali.aibaodan.cn/Article/details/gtrbufqjqv.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zhengqikj.top/Article/details/gtbrjnrkfp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shzxlz.cn/Article/details/gtcbvuoxky.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.ehwqpu.com/Article/details/gtponvijlc.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.shzxlz.cn/Article/details/gtqeglxziu.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpjbkomy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hysaishi.cn/Article/details/gtsggbujdn.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cucudq.cn/Article/details/gttujctzpl.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gthcstozhp.html

[E15] HTML 转义 / 反转义
来源：http://dali.snrcjt.cn/Article/details/gtiyhqnecm.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.yanxiufei.cn/Article/details/gtoibouyij.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gogol.net.cn/Article/details/gtnyxacrpv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.redwolf501.top/Article/details/gtmyoysubg.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtpehdznqp.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.xziqi.cn/Article/details/gtzftnnkvg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.tanke756.top/Article/details/gtysivnsff.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.316326.xyz/Article/details/gtnsofcibn.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtpdjxwvah.html

[E16] 数字千分位
来源：http://dali.jinqigufen.top/Article/details/gtnblasuer.html

Py:   f"{1234567:,}"
来源：http://dali.tian-w.cn/Article/details/gtbwtqrqip.html

PHP:  number_format(1234567);
来源：http://dali.sysykeji.top/Article/details/gtrejxaasa.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.zdqjudy.top/Article/details/gtkhqmcoot.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.xylfe.cn/Article/details/gtzkhdruio.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.xylfe.cn/Article/details/gtwnaqiarv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiwywfdiz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.birdmap.top/Article/details/gtpkzntqrl.html

C#:   1234567.ToString("N0")
来源：http://dali.ivvv.top/Article/details/gtcmhvttlb.html

[E17] 首字母大写
来源：http://dali.shuidangran.top/Article/details/gtidwgubao.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.yuxming.cn/Article/details/gtirtmaydk.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.yangfankeji.com/Article/details/gtxjfueqdz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.tian-w.cn/Article/details/gtguojozon.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtaqtzasgj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.xuanzx.com/Article/details/gtkccndnxs.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.hammf.cn/Article/details/gtqghtrlwk.html

Ruby: s.capitalize
来源：http://dali.jyoumei.cn/Article/details/gtvouvgdiz.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shzxlz.cn/Article/details/gtqqvvtixy.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gthqwbuygh.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.bjfxy.top/Article/details/gtqhvbyvtj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jlsjyb.cn/Article/details/gtwgrsggma.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.bjfxy.top/Article/details/gtxnztgwol.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cdnleiting.top/Article/details/gtkibrsdvo.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.jiagoushi.top/Article/details/gtgipxdnkk.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbkimsoub.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.zycfv.cn/Article/details/gtucplbbmk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.ivvv.top/Article/details/gtklzqzqiz.html

[E19] 多行文本按行拆分
来源：http://dali.aibaodan.cn/Article/details/gtikgwhrko.html

Py:   s.splitlines()
来源：http://dali.ehwqpu.com/Article/details/gtsvbpjbhs.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.jqgfzy.top/Article/details/gtgaigyjah.html

JS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gtujnizixc.html

TS:   s.split(/\r?\n/)
来源：http://dali.jqgfzy.top/Article/details/gttfrsbefm.html

Java: s.lines().toList()
来源：http://dali.jianghu66.top/Article/details/gtqdyglnex.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gtuwmasgyy.html

Ruby: s.lines
来源：http://dali.0kj1m.cn/Article/details/gtjegdcxjv.html

C#:   s.Split('\n')
来源：http://dali.316326.xyz/Article/details/gtjzwiptvc.html

[E20] 判断字符串是否为空
来源：http://dali.chenlongwang.top/Article/details/gtvqqzbvwj.html

Py:   if not s:
来源：http://dali.zycfv.cn/Article/details/gtjyjmnvud.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.svipenyu.cn/Article/details/gtqsbyejeu.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.shuidangran.top/Article/details/gtspxvbvmd.html

TS:   if (s === "") {}
来源：http://dali.feifeiyinyue.top/Article/details/gttauuamvu.html

Java: if (s.isEmpty()) {}
来源：http://dali.birdmap.top/Article/details/gthqaupkut.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gtogouzguy.html

Ruby: if s.empty?
来源：http://dali.sufxvd.cn/Article/details/gtnpxnwmko.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmztjrbkl.html

[E21] 超长截断加省略号
来源：http://dali.shangyingyoupin.top/Article/details/gtkakhyrjk.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzxkroeb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdwwhwwv.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.svipenyu.cn/Article/details/gtezofaoib.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.aizwys.cn/Article/details/gtxxtmeivr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gtfggpraoz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhongyouzk.top/Article/details/gtzfqcwjqo.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258888.top/Article/details/gtzkmaueqp.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yvedp.cn/Article/details/gtwbkncvqv.html

[E22] 字节长度与字符长度
来源：http://dali.316326.xyz/Article/details/gtkygscfjt.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.bjfxy.top/Article/details/gtygjlqpdr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.cucudq.cn/Article/details/gtevgfyveo.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.gzhubu.top/Article/details/gtsowjjchi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cdnleiting.top/Article/details/gttlxklxqt.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yanxiufei.cn/Article/details/gtwfluzvio.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtakmticlz.html

Ruby: s.bytesize;  s.length
来源：http://dali.yj202588.top/Article/details/gtdmzbdeeb.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.ehwqpu.com/Article/details/gtxgoemaax.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtwjlyknmh.html

F. 文件与目录
来源：http://dali.hammf.cn/Article/details/gtmnmpqtnj.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtlosrscwr.html

[F01] 读取整个文件
来源：http://dali.cheryme.top/Article/details/gtrhevjbfk.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj20258.top/Article/details/gtphaniffj.html

PHP:  file_get_contents("a.txt");
来源：http://dali.jqgfzy.top/Article/details/gtaogrobwv.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.haohaochexian.top/Article/details/gtabhrrqcy.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jinqigufen.top/Article/details/gtqodlnrqy.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.andypj.xyz/Article/details/gtwdoivmis.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.smart0.xyz/Article/details/gthqaoxocv.html

Ruby: File.read("a.txt")
来源：http://dali.zhengqikj.top/Article/details/gtxenvghrz.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.yangfankeji.com/Article/details/gtlduhqubn.html

[F02] 逐行读取文件
来源：http://dali.yonumen.top/Article/details/gtbprmrbeq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gtpsmznoya.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cqqwz.cn/Article/details/gtdsrsvhlb.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.smart0.xyz/Article/details/gtfujuvnns.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtypwuvlwg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.zhijiandao.cn/Article/details/gtmxpcxqdv.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.hnqzz.top/Article/details/gtpdyaafiy.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.tianlin.xyz/Article/details/gtpbseiheg.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gtqktwecyi.html

[F03] 写入文件（覆盖）
来源：http://dali.c1oappe.top/Article/details/gtlygmmaze.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.jyoumei.cn/Article/details/gtmtugizhi.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yuxming.cn/Article/details/gtbbmxycgb.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.wangshuangyany.cn/Article/details/gtrxhthvtc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiuibludv.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yongpay.top/Article/details/gtshhfeluk.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtajhargkl.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gtvcvfxbyy.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yongpay.top/Article/details/gtjchpesjv.html

[F04] 追加写入文件
来源：http://dali.jinqigfzy.top/Article/details/gtizklzolh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.mhx1999.top/Article/details/gtknxcbjbh.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jyoumei.cn/Article/details/gtvsmmltdq.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jlsjyb.cn/Article/details/gtgaekbagr.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.sysykeji.top/Article/details/gtblfnrwtc.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.daxiang520.top/Article/details/gtumoqlunu.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.feifeiyinyue.top/Article/details/gteqfvepzy.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.aibaodan.cn/Article/details/gtfrisetbo.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.sysykeji.top/Article/details/gtaimhqocg.html

[F05] 判断文件或目录是否存在
来源：http://dali.zhixingplan.top/Article/details/gtahyatjci.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.shangyingyoupin.top/Article/details/gtogxncelj.html

PHP:  file_exists("a.txt");
来源：http://dali.cashguo.top/Article/details/gtxjngifrs.html

JS:   fs.existsSync("a.txt")
来源：http://dali.xuanzx.com/Article/details/gtfmoqkenm.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtrwbipkkp.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.fzhhl.top/Article/details/gtqpwwgyrg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gttnoxqfqs.html

Ruby: File.exist?("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtajzvmndp.html

C#:   File.Exists("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtvcrcnauu.html

[F06] 删除文件
来源：http://dali.cashguo.top/Article/details/gtljuubxbe.html

Py:   os.remove("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtczkepxqj.html

PHP:  unlink("a.txt");
来源：http://dali.xuetiantiany.cn/Article/details/gtzfpjdspw.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gthlibcesa.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.gzhubu.top/Article/details/gtdtkadifv.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtjazirbfw.html

Go:   os.Remove("a.txt")
来源：http://dali.cashguo.top/Article/details/gtxakufxmx.html

Ruby: File.delete("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtrnedeciy.html

C#:   File.Delete("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gtcvfzdtwv.html

[F07] 创建目录（含多级）
来源：http://dali.yj20258888.top/Article/details/gtrccryvjh.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtdlhpktmk.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cqqwz.cn/Article/details/gttvodgxso.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yueranfly.top/Article/details/gtwdxoeiep.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.chenlongwang.top/Article/details/gtsdmxgehb.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.feifeiyinyue.top/Article/details/gtppkyyvea.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtxzvwxplw.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gzhubu.top/Article/details/gtvaxrbzja.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtbijixtyq.html

[F08] 遍历目录
来源：http://dali.xuanzx.com/Article/details/gtikeezalm.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.jqgufenzy.top/Article/details/gtnfgrirpg.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.xuetiantiany.cn/Article/details/gtpemqpvxc.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangdashe.top/Article/details/gtnqmeltye.html

TS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gtijitqauc.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.quarkkingdee.top/Article/details/gtfoewbgqi.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.ydzc1.top/Article/details/gtjredexya.html

Ruby: Dir.children("dir")
来源：http://dali.daria6918.cn/Article/details/gtwvocxrln.html

C#:   Directory.GetFiles("dir")
来源：http://dali.shangyingyoupin.top/Article/details/gtpzhdgpml.html

[F09] 获取文件大小
来源：http://dali.cqqwz.cn/Article/details/gtrjypydyg.html

Py:   os.path.getsize("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtkyuvakqd.html

PHP:  filesize("a.txt");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtacuqmrqv.html

JS:   fs.statSync("a.txt").size
来源：http://dali.dianchejie.cn/Article/details/gtzmqngjsq.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guannengcc.top/Article/details/gtxnmffwhn.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yj20258.top/Article/details/gtdtdlxkhq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yuanzhike.top/Article/details/gtvfyjclhl.html

Ruby: File.size("a.txt")
来源：http://dali.redwolf501.top/Article/details/gtffskqupt.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.hammf.cn/Article/details/gtdyauyquh.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.hnqzz.top/Article/details/gtmkwqihme.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtatykoots.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.daxiang520.top/Article/details/gtqffwgljd.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtudogtqqz.html

TS:   path.extname("a.txt")
来源：http://dali.nanxuanxn.top/Article/details/gtalrtxkmo.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.birdmap.top/Article/details/gtqxsjagqg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtrwxuuivb.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.wangdashe.top/Article/details/gtvlrurlrq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.0kj1m.cn/Article/details/gtcjrvmbos.html

[F11] 复制与移动文件
来源：http://dali.haohaochexian.top/Article/details/gtfxqciuar.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.xuetiantiany.cn/Article/details/gtgichnrpp.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.meibo888.top/Article/details/gtjmcffsob.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.0kj1m.cn/Article/details/gtuvsymifn.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.ybcxt.top/Article/details/gtpqoqgamy.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xuanzx.com/Article/details/gtaleujguh.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yonumen.top/Article/details/gtvypoddoy.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yongpay.top/Article/details/gtoivyidgh.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.c1oappe.top/Article/details/gtatmqwqxb.html

[F12] CSV 读写
来源：http://dali.pycfn.com/Article/details/gtykqhahfx.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.nanxuanxn.top/Article/details/gtddwspgnn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hongshengwenyu.top/Article/details/gtmixnshbo.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.yueranfly.top/Article/details/gtdifgxsxr.html

TS:   // 同上
来源：http://dali.yvedp.cn/Article/details/gtuvjtvqzx.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.shzxlz.cn/Article/details/gtbmlrxgav.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.zhoulong.xyz/Article/details/gtvrlgynnf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gtcqkpvfua.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrouktws.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtoyyopnnf.html

G. 面向对象
来源：http://dali.zhongyouzk.top/Article/details/gthsztnrub.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtetnjvjva.html

[G01] 定义类
来源：http://dali.xinyue.icu/Article/details/gtwsmwjbrp.html

Py:   class User: pass
来源：http://dali.xylfe.cn/Article/details/gtaqezvtgq.html

PHP:  class User {}
来源：http://dali.dashuyun.cn/Article/details/gtuagesvgt.html

JS:   class User {}
来源：http://dali.birdmap.top/Article/details/gtcjfrtrav.html

TS:   class User { name: string = ""; }
来源：http://dali.chenzaomai.com/Article/details/gtppderjna.html

Java: class User {}
来源：http://dali.xuetiantiany.cn/Article/details/gtdfcrraia.html

Go:   type User struct { Name string }
来源：http://dali.yongpay.top/Article/details/gtnzgkguyk.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gteatrrywm.html

C#:   class User {}
来源：http://dali.zhixingplan.top/Article/details/gtayizphvg.html

[G02] 构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtjltbsitt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmuguovyd.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.zhongyouzk.top/Article/details/gtmcpkbitg.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.cqqwz.cn/Article/details/gtgrstfsjo.html

TS:   constructor(public name: string) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtluqiadvg.html

Java: User(String name) { this.name = name; }
来源：http://dali.shuidangran.top/Article/details/gtdmepupcl.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.yonumen.top/Article/details/gtkoqxchee.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.haohaochexian.top/Article/details/gtqzdsjzpl.html

C#:   public User(string name) { Name = name; }
来源：http://dali.daxiang520.top/Article/details/gtjiyntlus.html

[G03] 实例属性
来源：http://dali.pengpengdd.cyou/Article/details/gtpvvyqqdb.html

Py:   self.name = "x"
来源：http://dali.xylfe.cn/Article/details/gtrosyoxqs.html

PHP:  public string $name = "x";
来源：http://dali.zycfv.cn/Article/details/gtqjbdxsfl.html

JS:   this.name = "x";
来源：http://dali.guannengcc.top/Article/details/gtofjtzfiz.html

TS:   name: string = "x";
来源：http://dali.shuidangran.top/Article/details/gtxmynqsvo.html

Java: private String name;
来源：http://dali.yonumen.top/Article/details/gtzuwtunfr.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtcejblbig.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gtkzelkiac.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.tanke756.top/Article/details/gtduedbkpl.html

[G04] 定义方法
来源：http://dali.yj20258888.top/Article/details/gtflxpsuhh.html

Py:   def greet(self): return self.name
来源：http://dali.havefunace.top/Article/details/gtpbarvlwc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gogol.net.cn/Article/details/gtzgcepwnl.html

JS:   greet() { return this.name; }
来源：http://dali.vqdsnc.cn/Article/details/gtkimdbnbo.html

TS:   greet(): string { return this.name; }
来源：http://dali.tanke756.top/Article/details/gtcwpibwqq.html

Java: String greet() { return name; }
来源：http://dali.guannengcc.top/Article/details/gtwaclpxmc.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.chenzaomai.com/Article/details/gtyhmijjoh.html

Ruby: def greet; @name; end
来源：http://dali.zhengqikj.top/Article/details/gtmvkzmuzu.html

C#:   public string Greet() => Name;
来源：http://dali.zhoulong.xyz/Article/details/gtzwplwxpy.html

[G05] 继承
来源：http://dali.yuxming.cn/Article/details/gtvpgwsbsi.html

Py:   class Admin(User): pass
来源：http://dali.gzhubu.top/Article/details/gtxgmxjnqe.html

PHP:  class Admin extends User {}
来源：http://dali.wangdashe.top/Article/details/gthbxbzsga.html

JS:   class Admin extends User {}
来源：http://dali.jinqigfzy.top/Article/details/gttflglpjc.html

TS:   class Admin extends User {}
来源：http://dali.jiagoushi.top/Article/details/gtloyzeima.html

Java: class Admin extends User {}
来源：http://dali.0kj1m.cn/Article/details/gttasicvks.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.zhijiandao.cn/Article/details/gtrsykegly.html

Ruby: class Admin < User; end
来源：http://dali.cdnleiting.top/Article/details/gtpurkaeog.html

C#:   class Admin : User {}
来源：http://dali.xuanzx.com/Article/details/gthmxoqfdf.html

[G06] 重写方法
来源：http://dali.sufxvd.cn/Article/details/gtfekgpnnj.html

Py:   def greet(self): return "admin"
来源：http://dali.9152youxi.cn/Article/details/gtlkwqozsa.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.quarkkingdee.top/Article/details/gtjtitptxl.html

JS:   greet() { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtawjxseue.html

TS:   greet(): string { return "admin"; }
来源：http://dali.kuanghao11.cn/Article/details/gtdvgmwqas.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxkxsnyzz.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cqqwz.cn/Article/details/gtlbtpdqxl.html

Ruby: def greet; "admin"; end
来源：http://dali.yj20258888.top/Article/details/gtwvugvhhc.html

C#:   public override string Greet() => "admin";
来源：http://dali.nanxuanxn.top/Article/details/gtootgufoj.html

[G07] 调用父类方法
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkflruxcy.html

Py:   super().greet()
来源：http://dali.fzhhl.top/Article/details/gtmvclgumh.html

PHP:  parent::greet();
来源：http://dali.hnqzz.top/Article/details/gtphgahsox.html

JS:   super.greet();
来源：http://dali.xinyue.icu/Article/details/gtwanikdxf.html

TS:   super.greet();
来源：http://dali.yanxiufei.cn/Article/details/gteeztvvdm.html

Java: super.greet();
来源：http://dali.nanxuanxn.top/Article/details/gtiwyepmsq.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.wangdashe.top/Article/details/gtgnvrhqbr.html

Ruby: super
来源：http://dali.iojbl.cn/Article/details/gtvoywbuob.html

C#:   base.Greet();
来源：http://dali.smart0.xyz/Article/details/gtgpkovfbl.html

[G08] 静态方法与属性
来源：http://dali.daria6918.cn/Article/details/gtmwvrklej.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.xuetiantiany.cn/Article/details/gtukifiqeg.html

PHP:  public static function f() {}
来源：http://dali.yueranfly.top/Article/details/gtiyewqbpq.html

JS:   static f() {}
来源：http://dali.sxryk.cn/Article/details/gtdqafdewa.html

TS:   static f(): void {}
来源：http://dali.yuanzhike.top/Article/details/gtrfjfnrkk.html

Java: static void f() {}
来源：http://dali.dianchejie.cn/Article/details/gthlqwngbc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.yangfankeji.com/Article/details/gtalkhuhyj.html

Ruby: def self.f; end
来源：http://dali.ivvv.top/Article/details/gtfzusemdq.html

C#:   public static void F() {}
来源：http://dali.fzhhl.top/Article/details/gtnrazwdjy.html

[G09] 接口 / 抽象类
来源：http://dali.yuanzhike.top/Article/details/gtzmbvdroo.html


<!-- 参考信息 -->