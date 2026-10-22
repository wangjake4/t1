代发 wailian999

PHP:  substr_count($s, "a");
来源：http://dali.hysaishi.cn/Article/details/gt2lsdtmnli.html

JS:   s.split("a").length - 1
来源：http://dali.pengpengdd.cyou/Article/details/gt2jcflascf.html

TS:   s.split("a").length - 1
来源：http://dali.cheryme.top/Article/details/gt2avydfzrj.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.zhixingplan.top/Article/details/gt2igviqwnw.html

Go:   strings.Count(s, "a")
来源：http://dali.hammf.cn/Article/details/gt2cnatfskf.html

Ruby: s.count("a")
来源：http://dali.birdmap.top/Article/details/gt2ngqdipuo.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2tlywdgzs.html

[E13] 逐字符遍历
来源：http://dali.hnqzz.top/Article/details/gt2pkdsebdg.html

Py:   for ch in s: print(ch)
来源：http://dali.xziqi.cn/Article/details/gt2rfxlmlcu.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.gzhubu.top/Article/details/gt2khvusxgz.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sweek.top/Article/details/gt2hroowyva.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gzhubu.top/Article/details/gt2fbnqqart.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.chenzaomai.com/Article/details/gt2fukvkitj.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.tian-w.cn/Article/details/gt2eceylgmv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.dashuyun.cn/Article/details/gt2vhwtfcxf.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hnxiangtu.top/Article/details/gt2qqdsoxqj.html

[E14] URL 编码与 Base64
来源：http://dali.hnqzz.top/Article/details/gt2xeuluyyw.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.xuanzx.com/Article/details/gt2pybazhza.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.haohaochexian.top/Article/details/gt2xqadesxy.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.dianchejie.cn/Article/details/gt2kaudbrov.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.yonumen.top/Article/details/gt2uqsuvbcr.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.tianlin.xyz/Article/details/gt2kweodzae.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhixingplan.top/Article/details/gt2kbnyjnxj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.yongpay.top/Article/details/gt2gpisikvx.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yvedp.cn/Article/details/gt2qsbxhvxf.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2aqxoprpg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.ppjwa.cn/Article/details/gt2ylgjjtbh.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhijiandao.cn/Article/details/gt2dfleucwk.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hfpthk.cn/Article/details/gt2lxezdwdv.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.chenlongwang.top/Article/details/gt2mqlxjnay.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gt2hdtmqevg.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.chenzaomai.com/Article/details/gt2krrzdzdx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhiwuduotai.top/Article/details/gt2szsonfth.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.chenzaomai.com/Article/details/gt2urrvkglh.html

[E16] 数字千分位
来源：http://dali.gaohongyu789.top/Article/details/gt2qdwjdrvm.html

Py:   f"{1234567:,}"
来源：http://dali.jqgufenzy.top/Article/details/gt2eztykqdg.html

PHP:  number_format(1234567);
来源：http://dali.ydzc1.top/Article/details/gt2dkqroegr.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.c1oappe.top/Article/details/gt2fqobkthe.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj20258.top/Article/details/gt2dqkkwjdx.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.0kj1m.cn/Article/details/gt2uutgvkyk.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2cdeuukpp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.andypj.xyz/Article/details/gt2ovixsmvo.html

C#:   1234567.ToString("N0")
来源：http://dali.yj202588.top/Article/details/gt2jentzims.html

[E17] 首字母大写
来源：http://dali.0kj1m.cn/Article/details/gt2bldflauo.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.sysykeji.top/Article/details/gt2stdmxvhf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daxiang520.top/Article/details/gt2gyvctsbu.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jinqigufen.top/Article/details/gt2lcscmsnq.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.c1oappe.top/Article/details/gt2prubnxbv.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2bevqwtwf.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.zhiwuduotai.top/Article/details/gt2wexzxbyz.html

Ruby: s.capitalize
来源：http://dali.dianchejie.cn/Article/details/gt2knncmmfb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.aibaodan.cn/Article/details/gt2wsqsxzpd.html

[E18] 模板占位符替换
来源：http://dali.yj202588.top/Article/details/gt2fcroggiw.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.fzhhl.top/Article/details/gt2gztjvgub.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cdcspyis.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.zdqjudy.top/Article/details/gt2wtyifejm.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.guowangkeji.top/Article/details/gt2oubugtng.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.yueranfly.top/Article/details/gt2wjhnnddz.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.yvedp.cn/Article/details/gt2qpbvifgr.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zikpnull.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jlsjyb.cn/Article/details/gt2rsvffhvb.html

[E19] 多行文本按行拆分
来源：http://dali.gzhubu.top/Article/details/gt2ohnrbwuz.html

Py:   s.splitlines()
来源：http://dali.chenjidiqi.icu/Article/details/gt2jtuboioj.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.yongpay.top/Article/details/gt2ufpbymsr.html

JS:   s.split(/\r?\n/)
来源：http://dali.sufxvd.cn/Article/details/gt2biljiwlu.html

TS:   s.split(/\r?\n/)
来源：http://dali.yj20258888.top/Article/details/gt2ovjgrbin.html

Java: s.lines().toList()
来源：http://dali.hongshengwenyu.top/Article/details/gt2vwduzysp.html

Go:   strings.Split(s, "\n")
来源：http://dali.9152youxi.cn/Article/details/gt2uufhbrzl.html

Ruby: s.lines
来源：http://dali.sysykeji.top/Article/details/gt2zsrgqztd.html

C#:   s.Split('\n')
来源：http://dali.daria6918.cn/Article/details/gt2rvrcjhjj.html

[E20] 判断字符串是否为空
来源：http://dali.zhengqikj.top/Article/details/gt2xvvxzfyh.html

Py:   if not s:
来源：http://dali.dianchejie.cn/Article/details/gt2uscfmidv.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgpcxgab.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cqqwz.cn/Article/details/gt2xydwynyu.html

TS:   if (s === "") {}
来源：http://dali.sufxvd.cn/Article/details/gt2zwcmcgow.html

Java: if (s.isEmpty()) {}
来源：http://dali.redwolf501.top/Article/details/gt2jitmdvvi.html

Go:   if s == "" {}
来源：http://dali.chenzaomai.com/Article/details/gt2jxafrjbv.html

Ruby: if s.empty?
来源：http://dali.dianchejie.cn/Article/details/gt2zvhnywrf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.hnxiangtu.top/Article/details/gt2ywpxjgei.html

[E21] 超长截断加省略号
来源：http://dali.fzhhl.top/Article/details/gt2fvpsnrcf.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zdqjudy.top/Article/details/gt2ndkctzgn.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.xuanzx.com/Article/details/gt2jszcybxl.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.pycfn.com/Article/details/gt2oobqbclh.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.mhx1999.top/Article/details/gt2xngegdgg.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gt2yceglkkr.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gt2fabbvxff.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hfpthk.cn/Article/details/gt2bnrreaxc.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.gaohongyu789.top/Article/details/gt2ztheezvx.html

[E22] 字节长度与字符长度
来源：http://dali.yuxming.cn/Article/details/gt2fduvdkmz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.dianchejie.cn/Article/details/gt2faudhuet.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.zycfv.cn/Article/details/gt2vdhkrktp.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.nanxinkj.top/Article/details/gt2tefqxeuo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tianlin.xyz/Article/details/gt2jrledfjp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.jinqigufen.top/Article/details/gt2tfebruvw.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.sxryk.cn/Article/details/gt2kwkgvwif.html

Ruby: s.bytesize;  s.length
来源：http://dali.daxiang520.top/Article/details/gt2qxiojrjh.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vytvkqyx.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gt2ahkjhjbi.html

F. 文件与目录
来源：http://dali.yj202588.top/Article/details/gt2uwjebgze.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2jlniqaiw.html

[F01] 读取整个文件
来源：http://dali.smart0.xyz/Article/details/gt2vqaitqhu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.yj202588.top/Article/details/gt2afplzttx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2eqjajvdz.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.hnqzz.top/Article/details/gt2kmfqxscb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2feszcxoj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.guannengcc.top/Article/details/gt2knjlpszy.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.cucudq.cn/Article/details/gt2widcvhge.html

Ruby: File.read("a.txt")
来源：http://dali.fzhhl.top/Article/details/gt2yjbdjyei.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2nqhjatkr.html

[F02] 逐行读取文件
来源：http://dali.mhx1999.top/Article/details/gt2igaesrwq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hysaishi.cn/Article/details/gt2zqroputu.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.ybcxt.top/Article/details/gt2mewoqlgz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.cqqwz.cn/Article/details/gt2xgfjbggn.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.jlsjyb.cn/Article/details/gt2ysdswccg.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.jqgfzy.top/Article/details/gt2yvzaekou.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.yanxiufei.cn/Article/details/gt2zfiwngrg.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.pengpengdd.cyou/Article/details/gt2afjflzrt.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.havefunace.top/Article/details/gt2mhooqokk.html

[F03] 写入文件（覆盖）
来源：http://dali.zhijiandao.cn/Article/details/gt2mchrymnx.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.havefunace.top/Article/details/gt2xstnyrao.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hnqzz.top/Article/details/gt2aeggoeok.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.guowangkeji.top/Article/details/gt2vnjbpzfc.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.xziqi.cn/Article/details/gt2vwwopjqs.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.cheryme.top/Article/details/gt2xgtwppwq.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yj20258888.top/Article/details/gt2ylnmwaou.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.jqgfzy.top/Article/details/gt2mxxdcpiq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.yanxiufei.cn/Article/details/gt2jgeoxoir.html

[F04] 追加写入文件
来源：http://dali.aibaodan.cn/Article/details/gt2mfkvchuc.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.sxryk.cn/Article/details/gt2fndncjdr.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylgittry.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.cashguo.top/Article/details/gt2tpgxizsk.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhoulong.xyz/Article/details/gt2xsctovtg.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zycfv.cn/Article/details/gt2jjckyzur.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yanxiufei.cn/Article/details/gt2aewprsfs.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shzxlz.cn/Article/details/gt2jasppcpp.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.yj20258.top/Article/details/gt2ovnjyoqy.html

[F05] 判断文件或目录是否存在
来源：http://dali.havefunace.top/Article/details/gt2utdjxoxv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.hysaishi.cn/Article/details/gt2xqubcute.html

PHP:  file_exists("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gt2oghwgryp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2tjnjkqgd.html

TS:   fs.existsSync("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2iwlhxnhr.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gt2bycigqsk.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xuetiantiany.cn/Article/details/gt2drvcmvxu.html

Ruby: File.exist?("a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2zcbktpxe.html

C#:   File.Exists("a.txt")
来源：http://dali.birdmap.top/Article/details/gt2qcdpnihx.html

[F06] 删除文件
来源：http://dali.ydzc1.top/Article/details/gt2lembzdze.html

Py:   os.remove("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2qboisosf.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2stpbegzn.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.ehwqpu.com/Article/details/gt2iknpnhch.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.vqdsnc.cn/Article/details/gt2tjrqunnm.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.hongshengwenyu.top/Article/details/gt2yybthabu.html

Go:   os.Remove("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2lyunvlmy.html

Ruby: File.delete("a.txt")
来源：http://dali.wangdashe.top/Article/details/gt2mumeixjg.html

C#:   File.Delete("a.txt");
来源：http://dali.xziqi.cn/Article/details/gt2coefvhfu.html

[F07] 创建目录（含多级）
来源：http://dali.xziqi.cn/Article/details/gt2oiuhrgfr.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.cdnleiting.top/Article/details/gt2tfzgdvkv.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.cdnleiting.top/Article/details/gt2nqxosmnk.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.svipenyu.cn/Article/details/gt2agdojlrw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.cashguo.top/Article/details/gt2wdrizthi.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.yanxiufei.cn/Article/details/gt2ewtyimgn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dbbakjmb.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.kuanghao11.cn/Article/details/gt2xvpgzcxf.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.sweek.top/Article/details/gt2lnghdmpi.html

[F08] 遍历目录
来源：http://dali.tian-w.cn/Article/details/gt2ykjtzrds.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.mhx1999.top/Article/details/gt2twkwnwfn.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.chenlongwang.top/Article/details/gt2qcoalmju.html

JS:   fs.readdirSync("dir")
来源：http://dali.tianlin.xyz/Article/details/gt2zljjqrxy.html

TS:   fs.readdirSync("dir")
来源：http://dali.jlsjyb.cn/Article/details/gt2dxwzgygu.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.jqgufenzy.top/Article/details/gt2bxbgggyr.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2itmvkkej.html

Ruby: Dir.children("dir")
来源：http://dali.birdmap.top/Article/details/gt2oyzopizw.html

C#:   Directory.GetFiles("dir")
来源：http://dali.9152youxi.cn/Article/details/gt2blaaobwb.html

[F09] 获取文件大小
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xqaderqf.html

Py:   os.path.getsize("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2fvlhkaea.html

PHP:  filesize("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gt2qyvhbkft.html

JS:   fs.statSync("a.txt").size
来源：http://dali.yj20258888.top/Article/details/gt2vqcvcdfs.html

TS:   fs.statSync("a.txt").size
来源：http://dali.sysykeji.top/Article/details/gt2togbddmc.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.yangfankeji.com/Article/details/gt2fameeime.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yvedp.cn/Article/details/gt2hemizaae.html

Ruby: File.size("a.txt")
来源：http://dali.chenzaomai.com/Article/details/gt2gijswpni.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.havefunace.top/Article/details/gt2qflumopg.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.chenzaomai.com/Article/details/gt2zmumtpze.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2dhrttfas.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cheryme.top/Article/details/gt2rnallydi.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2oyyvydln.html

TS:   path.extname("a.txt")
来源：http://dali.zhiwuduotai.top/Article/details/gt2rqykrzbp.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.gogol.net.cn/Article/details/gt2ecegbihf.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gt2hvdjegzq.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.xinyue.icu/Article/details/gt2vhqemejr.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.ppjwa.cn/Article/details/gt2uimwfmwe.html

[F11] 复制与移动文件
来源：http://dali.yongpay.top/Article/details/gt2adjiqqkw.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.dianchejie.cn/Article/details/gt2rwmbnqma.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2uhgywqre.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.sysykeji.top/Article/details/gt2dicodajc.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.iojbl.cn/Article/details/gt2vbuaipdp.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.sweek.top/Article/details/gt2tsysofsk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.iojbl.cn/Article/details/gt2zecupjbz.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2hpslhllx.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.yonumen.top/Article/details/gt2owkwtira.html

[F12] CSV 读写
来源：http://dali.dianchejie.cn/Article/details/gt2dfrodsix.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zdqjudy.top/Article/details/gt2wnosegzl.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yj20258888.top/Article/details/gt2ykjeeddd.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.hongshengwenyu.top/Article/details/gt2rwdpzdfa.html

TS:   // 同上
来源：http://dali.dianchejie.cn/Article/details/gt2ishgrkxn.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.zdqjudy.top/Article/details/gt2veegyfsr.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shzxlz.cn/Article/details/gt2fhyjinkr.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jqgfzy.top/Article/details/gt2ckfvbkma.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.andypj.xyz/Article/details/gt2jrvecihg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gt2chdzrbli.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gt2oymdfqdk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2wapicqhm.html

[G01] 定义类
来源：http://dali.haohaochexian.top/Article/details/gt2pvwfmmli.html

Py:   class User: pass
来源：http://dali.daria6918.cn/Article/details/gt2wedruedl.html

PHP:  class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2oagsdqwr.html

JS:   class User {}
来源：http://dali.chenlongwang.top/Article/details/gt2hplcvcla.html

TS:   class User { name: string = ""; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2brgvtiwh.html

Java: class User {}
来源：http://dali.ppjwa.cn/Article/details/gt2mhlafgui.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gt2gzzhnqfx.html

Ruby: class User; end
来源：http://dali.yueranfly.top/Article/details/gt2bflfsdur.html

C#:   class User {}
来源：http://dali.jqgfzy.top/Article/details/gt2qtdhukdn.html

[G02] 构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2pwsjhbnw.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.fengsongda.top/Article/details/gt2zqotrvds.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bfvijxhl.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.nanxuanxn.top/Article/details/gt2kjxkmopb.html

TS:   constructor(public name: string) {}
来源：http://dali.yj20258888.top/Article/details/gt2zozsyrei.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gt2sqghuzol.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.tianlin.xyz/Article/details/gt2fchkmcru.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.aibaodan.cn/Article/details/gt2jfhmican.html

C#:   public User(string name) { Name = name; }
来源：http://dali.haohaochexian.top/Article/details/gt2vwcplhmo.html

[G03] 实例属性
来源：http://dali.yonumen.top/Article/details/gt2hxqgxyqe.html

Py:   self.name = "x"
来源：http://dali.0kj1m.cn/Article/details/gt2daexerud.html

PHP:  public string $name = "x";
来源：http://dali.shangyingyoupin.top/Article/details/gt2ywnstnns.html

JS:   this.name = "x";
来源：http://dali.pengpengdd.cyou/Article/details/gt2jpnhosxw.html

TS:   name: string = "x";
来源：http://dali.cheryme.top/Article/details/gt2fixxqzod.html

Java: private String name;
来源：http://dali.birdmap.top/Article/details/gt2uraopsyo.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.dashuyun.cn/Article/details/gt2jsukdidw.html

Ruby: @name = "x"
来源：http://dali.wangdashe.top/Article/details/gt2zpsjxead.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.snrcjt.cn/Article/details/gt2nwjatheq.html

[G04] 定义方法
来源：http://dali.yuxming.cn/Article/details/gt2jgvmkpmq.html

Py:   def greet(self): return self.name
来源：http://dali.haohaochexian.top/Article/details/gt2llsmuhlx.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.jianghu66.top/Article/details/gt2anzwxoxs.html

JS:   greet() { return this.name; }
来源：http://dali.sxryk.cn/Article/details/gt2xetkfpbj.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2anitxtcg.html

Java: String greet() { return name; }
来源：http://dali.xuanzx.com/Article/details/gt2sncwuwgf.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.ppjwa.cn/Article/details/gt2oqkzgptz.html

Ruby: def greet; @name; end
来源：http://dali.jianghu66.top/Article/details/gt2uuxlngkm.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gt2hzwxmzey.html

[G05] 继承
来源：http://dali.shzxlz.cn/Article/details/gt2sfimehhj.html

Py:   class Admin(User): pass
来源：http://dali.zycfv.cn/Article/details/gt2vrahsaon.html

PHP:  class Admin extends User {}
来源：http://dali.hongshengwenyu.top/Article/details/gt2uzzzhmnb.html

JS:   class Admin extends User {}
来源：http://dali.bjfxy.top/Article/details/gt2sbvofskt.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2axsryizg.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gt2hyfmozcw.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.tanke756.top/Article/details/gt2nvjlfrkr.html

Ruby: class Admin < User; end
来源：http://dali.daria6918.cn/Article/details/gt2dyefyttn.html

C#:   class Admin : User {}
来源：http://dali.zhongyouzk.top/Article/details/gt2mescudos.html

[G06] 重写方法
来源：http://dali.yanxiufei.cn/Article/details/gt2glxgstfk.html

Py:   def greet(self): return "admin"
来源：http://dali.xuanzx.com/Article/details/gt2zrfvlqvh.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zycfv.cn/Article/details/gt2jkswzrxq.html

JS:   greet() { return "admin"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2znqewuav.html

TS:   greet(): string { return "admin"; }
来源：http://dali.tianlin.xyz/Article/details/gt2aqgsdtmt.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.havefunace.top/Article/details/gt2areuenty.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.xinyue.icu/Article/details/gt2kfghdedy.html

Ruby: def greet; "admin"; end
来源：http://dali.hfpthk.cn/Article/details/gt2wiktglbh.html

C#:   public override string Greet() => "admin";
来源：http://dali.jqgufenzy.top/Article/details/gt2tfbwwaex.html

[G07] 调用父类方法
来源：http://dali.jqgufenzy.top/Article/details/gt2uplgcjsv.html

Py:   super().greet()
来源：http://dali.chenzaomai.com/Article/details/gt2zwtqwpbd.html

PHP:  parent::greet();
来源：http://dali.zdqjudy.top/Article/details/gt2rghndzbh.html

JS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gt2dcmrzwcv.html

TS:   super.greet();
来源：http://dali.gotoacloud.top/Article/details/gt2bmkiebfp.html

Java: super.greet();
来源：http://dali.hysaishi.cn/Article/details/gt2miiatgnf.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ehwqpu.com/Article/details/gt2badiqxcn.html

Ruby: super
来源：http://dali.gzhubu.top/Article/details/gt2hsxqtmyw.html

C#:   base.Greet();
来源：http://dali.ehwqpu.com/Article/details/gt2uoqdsntz.html

[G08] 静态方法与属性
来源：http://dali.tanke756.top/Article/details/gt2giqzzgka.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nddjaxbs.html

PHP:  public static function f() {}
来源：http://dali.cashguo.top/Article/details/gt2icetxlgd.html

JS:   static f() {}
来源：http://dali.yonumen.top/Article/details/gt2bhmnakdp.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ymqorjbk.html

Java: static void f() {}
来源：http://dali.xuanzx.com/Article/details/gt2pjaitrfw.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jyoumei.cn/Article/details/gt2dahhpiry.html

Ruby: def self.f; end
来源：http://dali.jinghuilouyu.cn/Article/details/gt2meezlrey.html

C#:   public static void F() {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kodzkzce.html

[G09] 接口 / 抽象类
来源：http://dali.yuxming.cn/Article/details/gt2bglxlpwe.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.zhoulong.xyz/Article/details/gt2krhompdb.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2asqktyqu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.jinqigfzy.top/Article/details/gt2pwgmcpai.html

TS:   interface Shape { area(): number; }
来源：http://dali.jinqigufen.top/Article/details/gt2cmctucon.html

Java: interface Shape { double area(); }
来源：http://dali.yuxming.cn/Article/details/gt2yxxelalm.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.yj20258888.top/Article/details/gt2jqhrgusb.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.xuetiantiany.cn/Article/details/gt2dxgcmonj.html

C#:   interface IShape { double Area(); }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2whomwxpn.html

[G10] 访问控制
来源：http://dali.chenjidiqi.icu/Article/details/gt2ciwmjrhs.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.yueranfly.top/Article/details/gt2vgzowthp.html

PHP:  public / protected / private
来源：http://dali.sxryk.cn/Article/details/gt2vmwaoogt.html

JS:   #private 字段；其余公开
来源：http://dali.cashguo.top/Article/details/gt2yebosdko.html

TS:   public / protected / private
来源：http://dali.sufxvd.cn/Article/details/gt2ummudrzw.html

Java: public / protected / private / 默认包级
来源：http://dali.daxiang520.top/Article/details/gt2mwxncjow.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.xuanzx.com/Article/details/gt2ososqixv.html

Ruby: public / protected / private
来源：http://dali.hfpthk.cn/Article/details/gt2hkjnadrk.html


<!-- 参考信息 -->