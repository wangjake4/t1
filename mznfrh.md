代发 wailian999

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gt2fegxolwv.html

[E11] 反转字符串
来源：http://dali.daxiang520.top/Article/details/gt2fyhssbux.html

Py:   s[::-1]
来源：http://dali.zdqjudy.top/Article/details/gt2dljrezyz.html

PHP:  strrev($s);
来源：http://dali.andypj.xyz/Article/details/gt2fqpehfth.html

JS:   [...s].reverse().join("")
来源：http://dali.andypj.xyz/Article/details/gt2tnnpgxhi.html

TS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yygozmmr.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yvedp.cn/Article/details/gt2sucfcvrn.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.zhoulong.xyz/Article/details/gt2qgncksyx.html

Ruby: s.reverse
来源：http://dali.iojbl.cn/Article/details/gt2svcheupi.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.zhijiandao.cn/Article/details/gt2zecxpdrq.html

[E12] 统计某字符出现次数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nekcdkwd.html

Py:   s.count("a")
来源：http://dali.wangshuangyany.cn/Article/details/gt2sngmywer.html

PHP:  substr_count($s, "a");
来源：http://dali.jlsjyb.cn/Article/details/gt2asgbaelm.html

JS:   s.split("a").length - 1
来源：http://dali.aizwys.cn/Article/details/gt2mkqtpjhg.html

TS:   s.split("a").length - 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2myzrrxtk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yanxiufei.cn/Article/details/gt2acptphms.html

Go:   strings.Count(s, "a")
来源：http://dali.wangdashe.top/Article/details/gt2plmqrpgu.html

Ruby: s.count("a")
来源：http://dali.316326.xyz/Article/details/gt2rnunbswb.html

C#:   s.Count(c => c == 'a')
来源：http://dali.zhoulong.xyz/Article/details/gt2ozvgkwvx.html

[E13] 逐字符遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2chdauysu.html

Py:   for ch in s: print(ch)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pjrvibne.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dtwuwvff.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jiagoushi.top/Article/details/gt2wmbwvahd.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhixingplan.top/Article/details/gt2kfgwvonb.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.tianlin.xyz/Article/details/gt2jngzoydc.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.xziqi.cn/Article/details/gt2gmqnybfn.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.hywenlv.cn/Article/details/gt2xsyybbmp.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xphgjmac.html

[E14] URL 编码与 Base64
来源：http://dali.nanxinkj.top/Article/details/gt2gmbytusw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.mhx1999.top/Article/details/gt2oagclcxj.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.zhengqikj.top/Article/details/gt2ximknrzx.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zdqjudy.top/Article/details/gt2ditxldcf.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.birdmap.top/Article/details/gt2iucdtkof.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.hysaishi.cn/Article/details/gt2jqwmuult.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.wangshuangyany.cn/Article/details/gt2mabhdeje.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.cqqwz.cn/Article/details/gt2medbgeix.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2rbuspfjq.html

[E15] HTML 转义 / 反转义
来源：http://dali.xylfe.cn/Article/details/gt2svesaozr.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.fengsongda.top/Article/details/gt2wfxfacij.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.redwolf501.top/Article/details/gt2rxdlmyhv.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gt2obocohua.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.hammf.cn/Article/details/gt2frxmccoe.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.haohaochexian.top/Article/details/gt2nmekdtgf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yanxiufei.cn/Article/details/gt2qurmmkhu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.havefunace.top/Article/details/gt2mgqcjvnq.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.redwolf501.top/Article/details/gt2pqhqxvco.html

[E16] 数字千分位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cezvpfej.html

Py:   f"{1234567:,}"
来源：http://dali.xuanzx.com/Article/details/gt2erjustbq.html

PHP:  number_format(1234567);
来源：http://dali.zhengqikj.top/Article/details/gt2nlvnsskp.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.jyoumei.cn/Article/details/gt2uailxhkw.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2oxvydkbz.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.quarkkingdee.top/Article/details/gt2crbgwsfk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.andypj.xyz/Article/details/gt2iigupxfp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.9152youxi.cn/Article/details/gt2oqcciwmb.html

C#:   1234567.ToString("N0")
来源：http://dali.jqgfzy.top/Article/details/gt2tsppyamk.html

[E17] 首字母大写
来源：http://dali.havefunace.top/Article/details/gt2jnlryfhg.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.havefunace.top/Article/details/gt2butkamyv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ppduehwb.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.vqdsnc.cn/Article/details/gt2phzjatci.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.316326.xyz/Article/details/gt2nggviacj.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sweek.top/Article/details/gt2rskmjpfx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhengqikj.top/Article/details/gt2rezunfui.html

Ruby: s.capitalize
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2evoqaprf.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.hysaishi.cn/Article/details/gt2rbvipowf.html

[E18] 模板占位符替换
来源：http://dali.guowangkeji.top/Article/details/gt2bwnwlmqg.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.zhiwuduotai.top/Article/details/gt2sxhnkryk.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.sysykeji.top/Article/details/gt2gcndxnhq.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shzxlz.cn/Article/details/gt2xitaglyt.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.yuxming.cn/Article/details/gt2afgynizr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.daxiang520.top/Article/details/gt2lyougmlb.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.zhiwuduotai.top/Article/details/gt2euuclyyj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2fclljsua.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ymnnadeo.html

[E19] 多行文本按行拆分
来源：http://dali.havefunace.top/Article/details/gt2dmjooaka.html

Py:   s.splitlines()
来源：http://dali.shuidangran.top/Article/details/gt2uqramwhj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gt2fowrkjbw.html

JS:   s.split(/\r?\n/)
来源：http://dali.xylfe.cn/Article/details/gt2ebtawbpt.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gt2bfbxbrho.html

Java: s.lines().toList()
来源：http://dali.yj202588.top/Article/details/gt2abrvdlmy.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gt2qrlkjsgp.html

Ruby: s.lines
来源：http://dali.xuetiantiany.cn/Article/details/gt2fhwsauxx.html

C#:   s.Split('\n')
来源：http://dali.aibaodan.cn/Article/details/gt2ofxnyqjy.html

[E20] 判断字符串是否为空
来源：http://dali.quarkkingdee.top/Article/details/gt2ulirvjoh.html

Py:   if not s:
来源：http://dali.wangdashe.top/Article/details/gt2bgydxmso.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.birdmap.top/Article/details/gt2hafedsun.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.daria6918.cn/Article/details/gt2zumkowvl.html

TS:   if (s === "") {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tbfortpm.html

Java: if (s.isEmpty()) {}
来源：http://dali.feifeiyinyue.top/Article/details/gt2czoujemt.html

Go:   if s == "" {}
来源：http://dali.svipenyu.cn/Article/details/gt2nrisylqu.html

Ruby: if s.empty?
来源：http://dali.ydzc1.top/Article/details/gt2tbdykynf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.wangdashe.top/Article/details/gt2lofhajzw.html

[E21] 超长截断加省略号
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ktcxqfxg.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.yanxiufei.cn/Article/details/gt2jhnfvlva.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hfpthk.cn/Article/details/gt2hkjgfoxm.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.tanke756.top/Article/details/gt2rfkyvnjy.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.guowangkeji.top/Article/details/gt2nxfkevkc.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.feifeiyinyue.top/Article/details/gt2ixyeryqz.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xuanzx.com/Article/details/gt2pwjjbtqn.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2drxyzvgz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yangfankeji.com/Article/details/gt2hwqygoxc.html

[E22] 字节长度与字符长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bpkrrfyn.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.xinyue.icu/Article/details/gt2otlpskxm.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jyoumei.cn/Article/details/gt2tvqvruox.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.ydzc1.top/Article/details/gt2gwfpecgb.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.dianchejie.cn/Article/details/gt2bkbllkqf.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.wangdashe.top/Article/details/gt2fgctbiyh.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.nwbrower.top/Article/details/gt2wsnzqmlo.html

Ruby: s.bytesize;  s.length
来源：http://dali.gotoacloud.top/Article/details/gt2ctsigkwm.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.shangyingyoupin.top/Article/details/gt2xgtwkrjj.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gt2jifbssvh.html

F. 文件与目录
来源：http://dali.jianghu66.top/Article/details/gt2jqgcrpxt.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gt2ejhydbkv.html

[F01] 读取整个文件
来源：http://dali.gotoacloud.top/Article/details/gt2cnuzapfq.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.tianlin.xyz/Article/details/gt2aqyvjjvv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.havefunace.top/Article/details/gt2eyjvqxkl.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.guowangkeji.top/Article/details/gt2commigoh.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.jqgufenzy.top/Article/details/gt2cytlknmm.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbvznowy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.hammf.cn/Article/details/gt2vnowirqb.html

Ruby: File.read("a.txt")
来源：http://dali.mhx1999.top/Article/details/gt2vwasteiw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.daria6918.cn/Article/details/gt2virhszcb.html

[F02] 逐行读取文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2viwwjowk.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.316326.xyz/Article/details/gt2zubjzqkj.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jyoumei.cn/Article/details/gt2mfhhrlez.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hammf.cn/Article/details/gt2ytctvjtv.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywzswhph.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gt2utoeneeu.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.snrcjt.cn/Article/details/gt2igimegow.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.kuanghao11.cn/Article/details/gt2smpuylgy.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.shuidangran.top/Article/details/gt2akcaeqzt.html

[F03] 写入文件（覆盖）
来源：http://dali.aizwys.cn/Article/details/gt2wisjvxvc.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xabvlmkf.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.iojbl.cn/Article/details/gt2dfvownlj.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fengsongda.top/Article/details/gt2vlzufxtk.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.fzhhl.top/Article/details/gt2idyndayl.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.feifeiyinyue.top/Article/details/gt2dyboruhf.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.pengpengdd.cyou/Article/details/gt2halbpegt.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jiagoushi.top/Article/details/gt2tyxhsufr.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.chenlongwang.top/Article/details/gt2zwdsqrpc.html

[F04] 追加写入文件
来源：http://dali.kuanghao11.cn/Article/details/gt2xvgwbgyt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yuanzhike.top/Article/details/gt2acjrgadz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.jlsjyb.cn/Article/details/gt2syiemdak.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.ydzc1.top/Article/details/gt2wgjwyixd.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.iojbl.cn/Article/details/gt2pspiados.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dmvrpwgg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.chenjidiqi.icu/Article/details/gt2cxbjwgiw.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2unalcitu.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yvedp.cn/Article/details/gt2oblrcoiw.html

[F05] 判断文件或目录是否存在
来源：http://dali.wangdashe.top/Article/details/gt2sjepfsly.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yuxming.cn/Article/details/gt2fqopafdf.html

PHP:  file_exists("a.txt");
来源：http://dali.vqdsnc.cn/Article/details/gt2pkjdxqgt.html

JS:   fs.existsSync("a.txt")
来源：http://dali.sxryk.cn/Article/details/gt2axlazvvp.html

TS:   fs.existsSync("a.txt")
来源：http://dali.aibaodan.cn/Article/details/gt2vbvcdvzr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xinyue.icu/Article/details/gt2qrgwotzg.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gaohongyu789.top/Article/details/gt2iokifjsv.html

Ruby: File.exist?("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2aswenhrp.html

C#:   File.Exists("a.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2raxfthsf.html

[F06] 删除文件
来源：http://dali.xinyue.icu/Article/details/gt2exrkngfv.html

Py:   os.remove("a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gt2hxewqpag.html

PHP:  unlink("a.txt");
来源：http://dali.guowangkeji.top/Article/details/gt2anmqcjbs.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.cucudq.cn/Article/details/gt2wijzyohr.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zhijiandao.cn/Article/details/gt2sifsxejj.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.pengpengdd.cyou/Article/details/gt2mddunebs.html

Go:   os.Remove("a.txt")
来源：http://dali.bjfxy.top/Article/details/gt2oghawnzn.html

Ruby: File.delete("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2xrjeryth.html

C#:   File.Delete("a.txt");
来源：http://dali.tian-w.cn/Article/details/gt2vbmvhrtv.html

[F07] 创建目录（含多级）
来源：http://dali.tian-w.cn/Article/details/gt2vxiceepi.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.yongpay.top/Article/details/gt2aflvhkrw.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yonumen.top/Article/details/gt2eilgimnr.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.pengpengdd.cyou/Article/details/gt2zoqkkhbb.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.nanxuanxn.top/Article/details/gt2azwgezvk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.0kj1m.cn/Article/details/gt2hhaxtpyp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.yuxming.cn/Article/details/gt2zyacjemn.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yj20258888.top/Article/details/gt2wkuhgsqx.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.ybcxt.top/Article/details/gt2euzwgogj.html

[F08] 遍历目录
来源：http://dali.sysykeji.top/Article/details/gt2xljxhsfy.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xinyue.icu/Article/details/gt2qrpntkgp.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.hammf.cn/Article/details/gt2zqkisrbw.html

JS:   fs.readdirSync("dir")
来源：http://dali.snrcjt.cn/Article/details/gt2ltizyalt.html

TS:   fs.readdirSync("dir")
来源：http://dali.tanke756.top/Article/details/gt2molsyxzl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvuepvmb.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xuanzx.com/Article/details/gt2wibyncjm.html

Ruby: Dir.children("dir")
来源：http://dali.mhx1999.top/Article/details/gt2urnzobba.html

C#:   Directory.GetFiles("dir")
来源：http://dali.daxiang520.top/Article/details/gt2tapjkyaw.html

[F09] 获取文件大小
来源：http://dali.jiagoushi.top/Article/details/gt2rbvbzagk.html

Py:   os.path.getsize("a.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gvylumzn.html

PHP:  filesize("a.txt");
来源：http://dali.snrcjt.cn/Article/details/gt2qcjwmrsw.html

JS:   fs.statSync("a.txt").size
来源：http://dali.shuidangran.top/Article/details/gt2ivwmzaal.html

TS:   fs.statSync("a.txt").size
来源：http://dali.gzhubu.top/Article/details/gt2senylnka.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wdxaxeyu.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.jlsjyb.cn/Article/details/gt2ztbzlngd.html

Ruby: File.size("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2hxofiuka.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jqgfzy.top/Article/details/gt2uxjggtuv.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gt2mgrupnyk.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gt2obxmldan.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.yuanzhike.top/Article/details/gt2kxwqejvv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gt2bvxrcqsz.html

TS:   path.extname("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2fauuwtyu.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.bjfxy.top/Article/details/gt2zdruocdv.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2zqbnwvym.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2rzajadnw.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2rjausdat.html

[F11] 复制与移动文件
来源：http://dali.yj202588.top/Article/details/gt2tsgsdigt.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gt2wxlumusj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.guannengcc.top/Article/details/gt2zhdwfxvu.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxuanxn.top/Article/details/gt2qibajoum.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.haohaochexian.top/Article/details/gt2uqbytqnw.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.shuidangran.top/Article/details/gt2rfiktqej.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yvedp.cn/Article/details/gt2zsjkwcii.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnxiangtu.top/Article/details/gt2iqgzakrk.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gt2okjibhwt.html

[F12] CSV 读写
来源：http://dali.xuanzx.com/Article/details/gt2zebbkepr.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.redwolf501.top/Article/details/gt2oxagcdjg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.jqgufenzy.top/Article/details/gt2asskfexz.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.zhongyouzk.top/Article/details/gt2ahocwzoe.html

TS:   // 同上
来源：http://dali.zycfv.cn/Article/details/gt2rlrdbvta.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gotoacloud.top/Article/details/gt2uzsnuxqt.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gt2xkyrnmpn.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jiagoushi.top/Article/details/gt2whoxjslu.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.jinqigfzy.top/Article/details/gt2fnjuazqn.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2jkhlmfnp.html

G. 面向对象
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uigcpjkf.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xiaiochk.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gt2sberowlw.html

Py:   class User: pass
来源：http://dali.chenjidiqi.icu/Article/details/gt2aqwkllst.html

PHP:  class User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2nesdqrir.html

JS:   class User {}
来源：http://dali.sweek.top/Article/details/gt2cbzuafgt.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gt2oqbbcsij.html

Java: class User {}
来源：http://dali.jqgufenzy.top/Article/details/gt2dtshcdqe.html

Go:   type User struct { Name string }
来源：http://dali.jiagoushi.top/Article/details/gt2knataqvq.html

Ruby: class User; end
来源：http://dali.zhongyouzk.top/Article/details/gt2ayptkuzg.html

C#:   class User {}
来源：http://dali.cashguo.top/Article/details/gt2jogoxzlw.html

[G02] 构造函数
来源：http://dali.redwolf501.top/Article/details/gt2bbpihygm.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.aibaodan.cn/Article/details/gt2aghmgbre.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shangyingyoupin.top/Article/details/gt2bjlbwexo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.jqgufenzy.top/Article/details/gt2niogsnyt.html

TS:   constructor(public name: string) {}
来源：http://dali.ybcxt.top/Article/details/gt2qwseplrl.html

Java: User(String name) { this.name = name; }
来源：http://dali.xylfe.cn/Article/details/gt2tdshjaza.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cdnleiting.top/Article/details/gt2nhigplye.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.yuanzhike.top/Article/details/gt2rtsbqfka.html

C#:   public User(string name) { Name = name; }
来源：http://dali.ehwqpu.com/Article/details/gt2czueakcn.html

[G03] 实例属性
来源：http://dali.xinyue.icu/Article/details/gt2nnoyqmum.html

Py:   self.name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2ewswyxru.html

PHP:  public string $name = "x";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egcqhutn.html

JS:   this.name = "x";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zdfnilzl.html

TS:   name: string = "x";
来源：http://dali.xuanzx.com/Article/details/gt2puzecdij.html

Java: private String name;
来源：http://dali.ydzc1.top/Article/details/gt2qvjmaiqb.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hammf.cn/Article/details/gt2nbvebcdt.html

Ruby: @name = "x"
来源：http://dali.zhoulong.xyz/Article/details/gt2fxlrcqjt.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yangfankeji.com/Article/details/gt2wnrcllwl.html

[G04] 定义方法
来源：http://dali.sxryk.cn/Article/details/gt2dkervjih.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gt2djhlngrc.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.nanxinkj.top/Article/details/gt2xcyrncqn.html

JS:   greet() { return this.name; }
来源：http://dali.andypj.xyz/Article/details/gt2uemwgyvx.html

TS:   greet(): string { return this.name; }
来源：http://dali.hammf.cn/Article/details/gt2ufbmvffu.html

Java: String greet() { return name; }
来源：http://dali.hywenlv.cn/Article/details/gt2moqjyenw.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.sweek.top/Article/details/gt2xfhcddma.html

Ruby: def greet; @name; end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2semrcwyb.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gt2yehaphcv.html

[G05] 继承
来源：http://dali.xziqi.cn/Article/details/gt2vlhdnavp.html

Py:   class Admin(User): pass
来源：http://dali.yvedp.cn/Article/details/gt2rkarzwsu.html

PHP:  class Admin extends User {}
来源：http://dali.yangfankeji.com/Article/details/gt2cvhpwtmx.html

JS:   class Admin extends User {}
来源：http://dali.sxryk.cn/Article/details/gt2qfomcmwo.html

TS:   class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2iiwggkxu.html

Java: class Admin extends User {}
来源：http://dali.daria6918.cn/Article/details/gt2dtddwwib.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jqgfzy.top/Article/details/gt2flhgcnqv.html

Ruby: class Admin < User; end
来源：http://dali.yvedp.cn/Article/details/gt2cddnhtyf.html

C#:   class Admin : User {}
来源：http://dali.svipenyu.cn/Article/details/gt2bqosxqbc.html

[G06] 重写方法
来源：http://dali.mhx1999.top/Article/details/gt2jvgcnbgo.html

Py:   def greet(self): return "admin"
来源：http://dali.gaohongyu789.top/Article/details/gt2qnraovks.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.jqgfzy.top/Article/details/gt2qfjyjlec.html

JS:   greet() { return "admin"; }
来源：http://dali.sxryk.cn/Article/details/gt2blbhqehm.html

TS:   greet(): string { return "admin"; }
来源：http://dali.gotoacloud.top/Article/details/gt2kykjuezh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2iarqezmi.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.pengpengdd.cyou/Article/details/gt2ctwgsvru.html

Ruby: def greet; "admin"; end
来源：http://dali.jinqigufen.top/Article/details/gt2jjgwnaxt.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gt2uawnnipm.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gt2szzncjgq.html

Py:   super().greet()
来源：http://dali.snrcjt.cn/Article/details/gt2fwouuuhp.html

PHP:  parent::greet();
来源：http://dali.chenlongwang.top/Article/details/gt2fivhmpqe.html

JS:   super.greet();
来源：http://dali.jiagoushi.top/Article/details/gt2vmhbyres.html

TS:   super.greet();
来源：http://dali.ybcxt.top/Article/details/gt2dxotctkj.html

Java: super.greet();
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qzvdylty.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.daria6918.cn/Article/details/gt2zjxzbsmc.html

Ruby: super
来源：http://dali.c1oappe.top/Article/details/gt2sccbvqhm.html

C#:   base.Greet();
来源：http://dali.cdnleiting.top/Article/details/gt2iwrduxzp.html

[G08] 静态方法与属性
来源：http://dali.bjfxy.top/Article/details/gt2qmvdmwbp.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qmgpkrfd.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gt2iqsiopnn.html

JS:   static f() {}
来源：http://dali.zhongyouzk.top/Article/details/gt2yfgounyi.html

TS:   static f(): void {}
来源：http://dali.hnxiangtu.top/Article/details/gt2gzshintn.html

Java: static void f() {}
来源：http://dali.yangfankeji.com/Article/details/gt2kewnuefc.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.zhijiandao.cn/Article/details/gt2hqsaaagf.html

Ruby: def self.f; end
来源：http://dali.havefunace.top/Article/details/gt2gfnozwfp.html

C#:   public static void F() {}
来源：http://dali.dashuyun.cn/Article/details/gt2gnyxacia.html

[G09] 接口 / 抽象类
来源：http://dali.cheryme.top/Article/details/gt2snpihuhv.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.yangfankeji.com/Article/details/gt2cepajjry.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhabluvt.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.daxiang520.top/Article/details/gt2cvmgsbkd.html

TS:   interface Shape { area(): number; }
来源：http://dali.aibaodan.cn/Article/details/gt2nkimrsbb.html


<!-- 参考信息 -->