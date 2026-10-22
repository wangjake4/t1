代发 wailian999

JS:   [...s].reverse().join("")
来源：http://dali.cashguo.top/Article/details/gt2xzlmqdxl.html

TS:   [...s].reverse().join("")
来源：http://dali.jlsjyb.cn/Article/details/gt2ywwakocd.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.gotoacloud.top/Article/details/gt2olsqajib.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.gogol.net.cn/Article/details/gt2ulgaaiyi.html

Ruby: s.reverse
来源：http://dali.yuxming.cn/Article/details/gt2yimkhzeu.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.hammf.cn/Article/details/gt2duukmcga.html

[E12] 统计某字符出现次数
来源：http://dali.jqgufenzy.top/Article/details/gt2ehgmhgdh.html

Py:   s.count("a")
来源：http://dali.daxiang520.top/Article/details/gt2nqidbbsj.html

PHP:  substr_count($s, "a");
来源：http://dali.jinqigufen.top/Article/details/gt2klkftpry.html

JS:   s.split("a").length - 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2sgayzqym.html

TS:   s.split("a").length - 1
来源：http://dali.zycfv.cn/Article/details/gt2otaxxlmk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.tianlin.xyz/Article/details/gt2uvehnvpa.html

Go:   strings.Count(s, "a")
来源：http://dali.ppjwa.cn/Article/details/gt2pywvjwfw.html

Ruby: s.count("a")
来源：http://dali.jyoumei.cn/Article/details/gt2syyxkvde.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gt2esfipoig.html

[E13] 逐字符遍历
来源：http://dali.hammf.cn/Article/details/gt2gcixreve.html

Py:   for ch in s: print(ch)
来源：http://dali.sxryk.cn/Article/details/gt2rzotqvpr.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2lastjfwy.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hfpthk.cn/Article/details/gt2spavzrth.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gogol.net.cn/Article/details/gt2egtrojzq.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gt2fcgohycx.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.aizwys.cn/Article/details/gt2sbjvburn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.xuanzx.com/Article/details/gt2ajbxjavc.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2inxdkfgy.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gt2foollowm.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.ehwqpu.com/Article/details/gt2xdminvux.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.fengsongda.top/Article/details/gt2uekaaghp.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.jinqigufen.top/Article/details/gt2xjbdogwi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.hammf.cn/Article/details/gt2tqyxwtwf.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.mhx1999.top/Article/details/gt2adlhretl.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yqnkvmaj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.iojbl.cn/Article/details/gt2apeivkmy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.fzhhl.top/Article/details/gt2oizemcur.html

[E15] HTML 转义 / 反转义
来源：http://dali.yj202588.top/Article/details/gt2hhuqygiz.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ydzc1.top/Article/details/gt2fdsfzztc.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.tianlin.xyz/Article/details/gt2jatphacv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.chenzaomai.com/Article/details/gt2oszsujun.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.ydzc1.top/Article/details/gt2eeiztxst.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.zhengqikj.top/Article/details/gt2yaciyxxh.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gt2ivfrbtdd.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.hysaishi.cn/Article/details/gt2wmstgrzi.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncjlgklw.html

[E16] 数字千分位
来源：http://dali.xinyue.icu/Article/details/gt2lnjorjiq.html

Py:   f"{1234567:,}"
来源：http://dali.xinyue.icu/Article/details/gt2brxmlglu.html

PHP:  number_format(1234567);
来源：http://dali.gogol.net.cn/Article/details/gt2qikdhxem.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2xnvwfnjh.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.fengsongda.top/Article/details/gt2gdznzano.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yangfankeji.com/Article/details/gt2vuvsfubl.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.tian-w.cn/Article/details/gt2qhdowips.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.jqgfzy.top/Article/details/gt2afpdyxyp.html

C#:   1234567.ToString("N0")
来源：http://dali.wangdashe.top/Article/details/gt2ggbfdieu.html

[E17] 首字母大写
来源：http://dali.sweek.top/Article/details/gt2omklwhcw.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2dnpkknwj.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.sufxvd.cn/Article/details/gt2cfkssmkf.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.svipenyu.cn/Article/details/gt2jdwyphax.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xziqi.cn/Article/details/gt2hzynniyc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.gzhubu.top/Article/details/gt2mwaoritm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.xylfe.cn/Article/details/gt2mhizmlzh.html

Ruby: s.capitalize
来源：http://dali.shuidangran.top/Article/details/gt2zcxupkor.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gt2fujmnauu.html

[E18] 模板占位符替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fzarywii.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.sweek.top/Article/details/gt2fdzuchtk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.wangshuangyany.cn/Article/details/gt2iyuaegze.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2jukkymne.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2clksnlnu.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yj20258.top/Article/details/gt2xxjwuvqv.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.cashguo.top/Article/details/gt2nwrrtztk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.dianchejie.cn/Article/details/gt2mihchkul.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shzxlz.cn/Article/details/gt2hbgpdhuv.html

[E19] 多行文本按行拆分
来源：http://dali.zhengqikj.top/Article/details/gt2rufbpmny.html

Py:   s.splitlines()
来源：http://dali.sweek.top/Article/details/gt2pkbpspfm.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.chenlongwang.top/Article/details/gt2soekaets.html

JS:   s.split(/\r?\n/)
来源：http://dali.shzxlz.cn/Article/details/gt2fumvumcc.html

TS:   s.split(/\r?\n/)
来源：http://dali.wangshuangyany.cn/Article/details/gt2gtcobsgb.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gt2wmyvkhes.html

Go:   strings.Split(s, "\n")
来源：http://dali.hysaishi.cn/Article/details/gt2vhsvgqce.html

Ruby: s.lines
来源：http://dali.quarkkingdee.top/Article/details/gt2nwcdrjlo.html

C#:   s.Split('\n')
来源：http://dali.xuanzx.com/Article/details/gt2fbvymgms.html

[E20] 判断字符串是否为空
来源：http://dali.0kj1m.cn/Article/details/gt2ofmsswgu.html

Py:   if not s:
来源：http://dali.sufxvd.cn/Article/details/gt2nuahvfgt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.feifeiyinyue.top/Article/details/gt2wcxmkjje.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.kuanghao11.cn/Article/details/gt2wsxasazs.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gt2orgonxdf.html

Java: if (s.isEmpty()) {}
来源：http://dali.tanke756.top/Article/details/gt2lpdcivkb.html

Go:   if s == "" {}
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hvzzftbl.html

Ruby: if s.empty?
来源：http://dali.gaohongyu789.top/Article/details/gt2biollqkp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.gotoacloud.top/Article/details/gt2iqjrkzrh.html

[E21] 超长截断加省略号
来源：http://dali.daria6918.cn/Article/details/gt2jbzckyra.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.xylfe.cn/Article/details/gt2pupmyzob.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.cheryme.top/Article/details/gt2tauonbao.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guannengcc.top/Article/details/gt2ggakynoc.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shzxlz.cn/Article/details/gt2htuxmtua.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.snrcjt.cn/Article/details/gt2orxnmzzz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhiwuduotai.top/Article/details/gt2hhsbwsma.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.316326.xyz/Article/details/gt2cagwvddf.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.jqgufenzy.top/Article/details/gt2iupuotvq.html

[E22] 字节长度与字符长度
来源：http://dali.c1oappe.top/Article/details/gt2ymzhtdyk.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.chenzaomai.com/Article/details/gt2gzyiuxlf.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tianlin.xyz/Article/details/gt2ofoyqqfq.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dgfpcxwr.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.cheryme.top/Article/details/gt2isxoajvw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.zycfv.cn/Article/details/gt2nlhfkuau.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.shzxlz.cn/Article/details/gt2nnmxxipw.html

Ruby: s.bytesize;  s.length
来源：http://dali.yongpay.top/Article/details/gt2scxkhctj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gt2nzwktprd.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2beqotjug.html

F. 文件与目录
来源：http://dali.9152youxi.cn/Article/details/gt2ynkjyzup.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2tfiaszcc.html

[F01] 读取整个文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2ivhzqzwu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tqfzuscz.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2xjtwijke.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.zhongyouzk.top/Article/details/gt2gbmhnlrw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.ehwqpu.com/Article/details/gt2dtdxztoq.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.0kj1m.cn/Article/details/gt2sbtdnydi.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.zhengqikj.top/Article/details/gt2huvurdbk.html

Ruby: File.read("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2neepaead.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.jianghu66.top/Article/details/gt2cakmvbdy.html

[F02] 逐行读取文件
来源：http://dali.sxryk.cn/Article/details/gt2nyxivufz.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhijiandao.cn/Article/details/gt2ujszftck.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.shuidangran.top/Article/details/gt2jfuvrmxj.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.nwbrower.top/Article/details/gt2liegligf.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.zhengqikj.top/Article/details/gt2nfsfemus.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.sysykeji.top/Article/details/gt2iuogtedi.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.shuidangran.top/Article/details/gt2eotlcxuo.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.0kj1m.cn/Article/details/gt2jzmzcggb.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hfpthk.cn/Article/details/gt2tioernkv.html

[F03] 写入文件（覆盖）
来源：http://dali.jinqigufen.top/Article/details/gt2xvxnkwfs.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.quarkkingdee.top/Article/details/gt2ldbicvup.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.jinqigfzy.top/Article/details/gt2dihnwwrh.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ahwsoylf.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2aaqssrcl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.sysykeji.top/Article/details/gt2buarheqv.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.svipenyu.cn/Article/details/gt2kvkszfuy.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hongshengwenyu.top/Article/details/gt2kgwnjpkr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2zdhxjetv.html

[F04] 追加写入文件
来源：http://dali.hywenlv.cn/Article/details/gt2lhmlnqii.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gzhubu.top/Article/details/gt2qymlfxkz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gt2llbagtje.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2ksuxijpz.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.hysaishi.cn/Article/details/gt2kzprjiau.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.c1oappe.top/Article/details/gt2mzwozyav.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.cqqwz.cn/Article/details/gt2apjxbxow.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.gotoacloud.top/Article/details/gt2pprvpyov.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.ydzc1.top/Article/details/gt2vkwcsauk.html

[F05] 判断文件或目录是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rchcyqxc.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.sweek.top/Article/details/gt2ovxgmwbz.html

PHP:  file_exists("a.txt");
来源：http://dali.gotoacloud.top/Article/details/gt2cujsnocd.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2boqiltom.html

TS:   fs.existsSync("a.txt")
来源：http://dali.yvedp.cn/Article/details/gt2phquderb.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.birdmap.top/Article/details/gt2dvqkefzl.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vilusfca.html

Ruby: File.exist?("a.txt")
来源：http://dali.tian-w.cn/Article/details/gt2elinrfjx.html

C#:   File.Exists("a.txt")
来源：http://dali.zycfv.cn/Article/details/gt2poqtasju.html

[F06] 删除文件
来源：http://dali.nanxuanxn.top/Article/details/gt2lniubptn.html

Py:   os.remove("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gt2pzaggnbt.html

PHP:  unlink("a.txt");
来源：http://dali.chenzaomai.com/Article/details/gt2frqxdito.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2coiuzvlc.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gt2mvrwbxgz.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uzcnkpxn.html

Go:   os.Remove("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2bhbaowlx.html

Ruby: File.delete("a.txt")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2euxfrmsl.html

C#:   File.Delete("a.txt");
来源：http://dali.xylfe.cn/Article/details/gt2fczdlbgf.html

[F07] 创建目录（含多级）
来源：http://dali.hfpthk.cn/Article/details/gt2vexzwlub.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.aizwys.cn/Article/details/gt2bvuvbgqz.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.xylfe.cn/Article/details/gt2uhryatuw.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.daria6918.cn/Article/details/gt2takbwrpk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gt2nxqhfegu.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.9152youxi.cn/Article/details/gt2dvfbulbz.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jyoumei.cn/Article/details/gt2rrdxaykq.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dlrrvhpf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.guannengcc.top/Article/details/gt2qadiacmb.html

[F08] 遍历目录
来源：http://dali.zhixingplan.top/Article/details/gt2kdbxsnle.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.cdnleiting.top/Article/details/gt2bnstkumj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.c1oappe.top/Article/details/gt2zijemvpk.html

JS:   fs.readdirSync("dir")
来源：http://dali.wangshuangyany.cn/Article/details/gt2bpbbusib.html

TS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gt2noywhllz.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gzhubu.top/Article/details/gt2fbfyyuxr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cdnleiting.top/Article/details/gt2crmkiogp.html

Ruby: Dir.children("dir")
来源：http://dali.ehwqpu.com/Article/details/gt2rzbfspwx.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yvedp.cn/Article/details/gt2ovdawvjp.html

[F09] 获取文件大小
来源：http://dali.hnqzz.top/Article/details/gt2ljnyxlpx.html

Py:   os.path.getsize("a.txt")
来源：http://dali.zhoulong.xyz/Article/details/gt2ldmsupqz.html

PHP:  filesize("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2wzipabrz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gt2mslruedc.html

TS:   fs.statSync("a.txt").size
来源：http://dali.xziqi.cn/Article/details/gt2mytngqnj.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2kelkioen.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yonumen.top/Article/details/gt2trxxbind.html

Ruby: File.size("a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2xqreldzo.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.yonumen.top/Article/details/gt2oictjevw.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2flmtiwnl.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2qxapalrt.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2sxkbtwub.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2evphzsgc.html

TS:   path.extname("a.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2kznbeyxv.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.jqgfzy.top/Article/details/gt2dydhdnon.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ivvv.top/Article/details/gt2dmgnpvyc.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gt2pedbaxmc.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2rfbdbbvn.html

[F11] 复制与移动文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ennwzxgl.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gt2auvvyydl.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2nqqbnrlq.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj202588.top/Article/details/gt2vodmcevr.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2izxxxyed.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cogbjlxg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.shangyingyoupin.top/Article/details/gt2jxlrwzkl.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yuxming.cn/Article/details/gt2czultmkb.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sxryk.cn/Article/details/gt2fyexubbi.html

[F12] CSV 读写
来源：http://dali.zhoulong.xyz/Article/details/gt2fnaigvzf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.ppjwa.cn/Article/details/gt2skoxmtps.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.zhixingplan.top/Article/details/gt2xdkohlal.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangdashe.top/Article/details/gt2jesrmlmf.html

TS:   // 同上
来源：http://dali.nwbrower.top/Article/details/gt2yucosfzf.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.jlsjyb.cn/Article/details/gt2uumipyeb.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.kuanghao11.cn/Article/details/gt2mkkzvwus.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ybcxt.top/Article/details/gt2vmeadmqh.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnqzz.top/Article/details/gt2ewqwozyq.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2vjeaeosm.html

G. 面向对象
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2punyrzoi.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdfixtjl.html

[G01] 定义类
来源：http://dali.iojbl.cn/Article/details/gt2hzojcctc.html

Py:   class User: pass
来源：http://dali.hammf.cn/Article/details/gt2uyhsugdt.html

PHP:  class User {}
来源：http://dali.cdnleiting.top/Article/details/gt2vtglrbxt.html

JS:   class User {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ehmmfhwh.html

TS:   class User { name: string = ""; }
来源：http://dali.ydzc1.top/Article/details/gt2pesnblpb.html

Java: class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2ckbaacnd.html

Go:   type User struct { Name string }
来源：http://dali.xziqi.cn/Article/details/gt2xwnmzarr.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gt2juyevoxa.html

C#:   class User {}
来源：http://dali.ydzc1.top/Article/details/gt2qarusvws.html

[G02] 构造函数
来源：http://dali.0kj1m.cn/Article/details/gt2kpuimrcs.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.sweek.top/Article/details/gt2tijquvlx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.chenzaomai.com/Article/details/gt2bfuolbjj.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2czhlubaw.html

TS:   constructor(public name: string) {}
来源：http://dali.sysykeji.top/Article/details/gt2boxxcqnl.html

Java: User(String name) { this.name = name; }
来源：http://dali.hysaishi.cn/Article/details/gt2rxwntmdw.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.hywenlv.cn/Article/details/gt2juppltck.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itwfbrma.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hfpthk.cn/Article/details/gt2gjtlvivq.html

[G03] 实例属性
来源：http://dali.yueranfly.top/Article/details/gt2eabmbndx.html

Py:   self.name = "x"
来源：http://dali.daxiang520.top/Article/details/gt2ewcbsjep.html

PHP:  public string $name = "x";
来源：http://dali.jlsjyb.cn/Article/details/gt2zsvlkfsc.html

JS:   this.name = "x";
来源：http://dali.ydzc1.top/Article/details/gt2wgelirio.html

TS:   name: string = "x";
来源：http://dali.cqqwz.cn/Article/details/gt2cwkmwjvm.html

Java: private String name;
来源：http://dali.nanxinkj.top/Article/details/gt2dkvhkirp.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.guowangkeji.top/Article/details/gt2wzbutnfh.html

Ruby: @name = "x"
来源：http://dali.sysykeji.top/Article/details/gt2krvkumbk.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.dianchejie.cn/Article/details/gt2sdrxpotv.html

[G04] 定义方法
来源：http://dali.gogol.net.cn/Article/details/gt2lrwzoirp.html

Py:   def greet(self): return self.name
来源：http://dali.xylfe.cn/Article/details/gt2egetvapp.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.redwolf501.top/Article/details/gt2rnrayamv.html

JS:   greet() { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gt2bgxnzmsf.html

TS:   greet(): string { return this.name; }
来源：http://dali.hnqzz.top/Article/details/gt2rcgkygii.html

Java: String greet() { return name; }
来源：http://dali.jinqigufen.top/Article/details/gt2izmjwpkv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jyoumei.cn/Article/details/gt2zkdfdmxo.html

Ruby: def greet; @name; end
来源：http://dali.nwbrower.top/Article/details/gt2wdegzeeo.html

C#:   public string Greet() => Name;
来源：http://dali.yj202588.top/Article/details/gt2wujlycnz.html

[G05] 继承
来源：http://dali.sxryk.cn/Article/details/gt2tgmskydc.html

Py:   class Admin(User): pass
来源：http://dali.yj20258888.top/Article/details/gt2mqticzcd.html

PHP:  class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgfvyamq.html

JS:   class Admin extends User {}
来源：http://dali.tian-w.cn/Article/details/gt2aijqjutn.html

TS:   class Admin extends User {}
来源：http://dali.zhoulong.xyz/Article/details/gt2ezuwjqma.html

Java: class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2jxkaguly.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikxwlmvm.html

Ruby: class Admin < User; end
来源：http://dali.sweek.top/Article/details/gt2awrbtqzc.html

C#:   class Admin : User {}
来源：http://dali.jyoumei.cn/Article/details/gt2qnwjxwkq.html

[G06] 重写方法
来源：http://dali.guowangkeji.top/Article/details/gt2upanuapv.html

Py:   def greet(self): return "admin"
来源：http://dali.bjfxy.top/Article/details/gt2gnxwphvh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.hysaishi.cn/Article/details/gt2dsgqiujl.html

JS:   greet() { return "admin"; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2zecibvtx.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gt2lrjskxqd.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.jiagoushi.top/Article/details/gt2quaqxupq.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.daxiang520.top/Article/details/gt2xoxcoplj.html

Ruby: def greet; "admin"; end
来源：http://dali.yongpay.top/Article/details/gt2jzvczrkd.html

C#:   public override string Greet() => "admin";
来源：http://dali.zhoulong.xyz/Article/details/gt2zwcsdgxu.html

[G07] 调用父类方法
来源：http://dali.xuetiantiany.cn/Article/details/gt2lswdkapz.html

Py:   super().greet()
来源：http://dali.mhx1999.top/Article/details/gt2emazlkzg.html

PHP:  parent::greet();
来源：http://dali.gaohongyu789.top/Article/details/gt2yqdwuxvk.html

JS:   super.greet();
来源：http://dali.jlsjyb.cn/Article/details/gt2hvkhycvk.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gt2fptvysbu.html

Java: super.greet();
来源：http://dali.nanxinkj.top/Article/details/gt2zmtljcos.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gt2hsamkdku.html

Ruby: super
来源：http://dali.jlsjyb.cn/Article/details/gt2zdnxwbtk.html

C#:   base.Greet();
来源：http://dali.jiagoushi.top/Article/details/gt2iqssbaha.html

[G08] 静态方法与属性
来源：http://dali.kuanghao11.cn/Article/details/gt2smwwpnrd.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shuidangran.top/Article/details/gt2rcneecfp.html

PHP:  public static function f() {}
来源：http://dali.tian-w.cn/Article/details/gt2rxztbdvc.html

JS:   static f() {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ubgmzexz.html

TS:   static f(): void {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2anfzqwqt.html

Java: static void f() {}
来源：http://dali.aibaodan.cn/Article/details/gt2dtsddfcc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.shuidangran.top/Article/details/gt2vlgyyyzd.html

Ruby: def self.f; end
来源：http://dali.xuanzx.com/Article/details/gt2tfsmakuv.html

C#:   public static void F() {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2crevseao.html

[G09] 接口 / 抽象类
来源：http://dali.meibo888.top/Article/details/gt2glfvurzr.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.ppjwa.cn/Article/details/gt2uihxtnhe.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.fzhhl.top/Article/details/gt2hxxmiutk.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.xylfe.cn/Article/details/gt2wvnskpen.html

TS:   interface Shape { area(): number; }
来源：http://dali.bjfxy.top/Article/details/gt2npshuzrj.html

Java: interface Shape { double area(); }
来源：http://dali.zhongyouzk.top/Article/details/gt2wkikvdtm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.chenjidiqi.icu/Article/details/gt2nhkwprkb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.tian-w.cn/Article/details/gt2vrlwuvjn.html

C#:   interface IShape { double Area(); }
来源：http://dali.ivvv.top/Article/details/gt2dqdaiexs.html


<!-- 参考信息 -->