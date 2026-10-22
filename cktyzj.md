代发 wailian999

Go:   strings.Count(s, "a")
来源：http://dali.guowangkeji.top/Article/details/gt2iddzynpv.html

Ruby: s.count("a")
来源：http://dali.ppjwa.cn/Article/details/gt2gowvyqnn.html

C#:   s.Count(c => c == 'a')
来源：http://dali.vqdsnc.cn/Article/details/gt2divlyfzn.html

[E13] 逐字符遍历
来源：http://dali.hnxiangtu.top/Article/details/gt2rozcggiu.html

Py:   for ch in s: print(ch)
来源：http://dali.ppjwa.cn/Article/details/gt2vkfctiut.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.fengsongda.top/Article/details/gt2znxpkciq.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.zhongyouzk.top/Article/details/gt2fnpalqdm.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.sxryk.cn/Article/details/gt2rypcyepe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.meibo888.top/Article/details/gt2ehkzbtiu.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.jianghu66.top/Article/details/gt2itoluzao.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.jqgufenzy.top/Article/details/gt2pimeowmk.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.tanke756.top/Article/details/gt2bowzetcc.html

[E14] URL 编码与 Base64
来源：http://dali.pengpengdd.cyou/Article/details/gt2recjrtaj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.bjfxy.top/Article/details/gt2hndxkywp.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.birdmap.top/Article/details/gt2xdsfpbtw.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yj202588.top/Article/details/gt2yfcjnqtu.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2tmydzyss.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.sxryk.cn/Article/details/gt2npuxziqp.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.birdmap.top/Article/details/gt2rwagomwj.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.xziqi.cn/Article/details/gt2bnhdbxoh.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.jiagoushi.top/Article/details/gt2ngsybjgf.html

[E15] HTML 转义 / 反转义
来源：http://dali.sweek.top/Article/details/gt2njfcftga.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.aizwys.cn/Article/details/gt2dvwiresq.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yvedp.cn/Article/details/gt2pdsudylc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sxryk.cn/Article/details/gt2ejtxygtp.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.nwbrower.top/Article/details/gt2idnsfrrl.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.jiagoushi.top/Article/details/gt2jqbfvydt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xinyue.icu/Article/details/gt2bjzasiwi.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2tbhfkeoe.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.svipenyu.cn/Article/details/gt2ttfueqxh.html

[E16] 数字千分位
来源：http://dali.zdqjudy.top/Article/details/gt2rtkbqgkl.html

Py:   f"{1234567:,}"
来源：http://dali.haohaochexian.top/Article/details/gt2rfdjdwkx.html

PHP:  number_format(1234567);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xaugwnuo.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.yongpay.top/Article/details/gt2vekyxffu.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.iojbl.cn/Article/details/gt2mmvtoszo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.yonumen.top/Article/details/gt2lbxunvsy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.kuanghao11.cn/Article/details/gt2qvntxhsm.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.xinyue.icu/Article/details/gt2ntjaquws.html

C#:   1234567.ToString("N0")
来源：http://dali.chenlongwang.top/Article/details/gt2repmgnri.html

[E17] 首字母大写
来源：http://dali.jinqigfzy.top/Article/details/gt2huidklut.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.zhengqikj.top/Article/details/gt2jnwshgmv.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.havefunace.top/Article/details/gt2kugmynyw.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cashguo.top/Article/details/gt2imahhqdl.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.daria6918.cn/Article/details/gt2hvwmkqcc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.yvedp.cn/Article/details/gt2rbettvax.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.guannengcc.top/Article/details/gt2dkqaxefk.html

Ruby: s.capitalize
来源：http://dali.sysykeji.top/Article/details/gt2jivazutw.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.ivvv.top/Article/details/gt2rmjkcsqv.html

[E18] 模板占位符替换
来源：http://dali.zhongyouzk.top/Article/details/gt2ozjfikgy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.quarkkingdee.top/Article/details/gt2xlziadgj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.haohaochexian.top/Article/details/gt2thkzbbkh.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vggywngp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.andypj.xyz/Article/details/gt2uajxagfh.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.c1oappe.top/Article/details/gt2ziynqeay.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gt2mivxdcza.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.guannengcc.top/Article/details/gt2rtqzkplt.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.shuidangran.top/Article/details/gt2piqwxvoz.html

[E19] 多行文本按行拆分
来源：http://dali.yangfankeji.com/Article/details/gt2glmjvqhg.html

Py:   s.splitlines()
来源：http://dali.quarkkingdee.top/Article/details/gt2kgifhxxh.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tkscxbbs.html

JS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gt2lftiepaj.html

TS:   s.split(/\r?\n/)
来源：http://dali.shuidangran.top/Article/details/gt2ppqdcnwi.html

Java: s.lines().toList()
来源：http://dali.yueranfly.top/Article/details/gt2oltuwssi.html

Go:   strings.Split(s, "\n")
来源：http://dali.gogol.net.cn/Article/details/gt2bqaueuvf.html

Ruby: s.lines
来源：http://dali.yueranfly.top/Article/details/gt2czlwusdh.html

C#:   s.Split('\n')
来源：http://dali.yanxiufei.cn/Article/details/gt2upjixzcy.html

[E20] 判断字符串是否为空
来源：http://dali.yj20258888.top/Article/details/gt2cwlmceji.html

Py:   if not s:
来源：http://dali.chenlongwang.top/Article/details/gt2zyukugmo.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.hongshengwenyu.top/Article/details/gt2qduzjzin.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yuanzhike.top/Article/details/gt2edfhbbsb.html

TS:   if (s === "") {}
来源：http://dali.zdqjudy.top/Article/details/gt2bnzxpiwn.html

Java: if (s.isEmpty()) {}
来源：http://dali.wangdashe.top/Article/details/gt2awmvxbws.html

Go:   if s == "" {}
来源：http://dali.shuidangran.top/Article/details/gt2btoupdrx.html

Ruby: if s.empty?
来源：http://dali.hywenlv.cn/Article/details/gt2ufqjhitd.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ehwstyoy.html

[E21] 超长截断加省略号
来源：http://dali.chenzaomai.com/Article/details/gt2fieqfgje.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.birdmap.top/Article/details/gt2qkbhelsb.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2vitsrduf.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.vqdsnc.cn/Article/details/gt2lrehxahd.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jnxfwkfv.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.jlsjyb.cn/Article/details/gt2yylbfgjl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.hnqzz.top/Article/details/gt2zuxuuhqr.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.xinyue.icu/Article/details/gt2anzmruyb.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.wangshuangyany.cn/Article/details/gt2ktywscot.html

[E22] 字节长度与字符长度
来源：http://dali.yonumen.top/Article/details/gt2zwdsmzoc.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.zycfv.cn/Article/details/gt2hkcikgan.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.sufxvd.cn/Article/details/gt2wlkkslsb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yj202588.top/Article/details/gt2poggrvvt.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hammf.cn/Article/details/gt2rbcthklq.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.yvedp.cn/Article/details/gt2igqpwxyv.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gt2bqlmqhwm.html

Ruby: s.bytesize;  s.length
来源：http://dali.sweek.top/Article/details/gt2tlugtkou.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.kuanghao11.cn/Article/details/gt2qfyqwfje.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2ccymzbbg.html

F. 文件与目录
来源：http://dali.cashguo.top/Article/details/gt2cqdfatio.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2mojxbcqi.html

[F01] 读取整个文件
来源：http://dali.yj20258.top/Article/details/gt2flnjsnsw.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.0kj1m.cn/Article/details/gt2rdvgszfo.html

PHP:  file_get_contents("a.txt");
来源：http://dali.zhoulong.xyz/Article/details/gt2jbsswbwf.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.tianlin.xyz/Article/details/gt2jwuuahaw.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gt2rtclvjqj.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.dashuyun.cn/Article/details/gt2rnfzryby.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.aibaodan.cn/Article/details/gt2pnkeoasf.html

Ruby: File.read("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2shkzlrbq.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gt2ejxlfhft.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gt2bktkqqkg.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2elnadrel.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.cdnleiting.top/Article/details/gt2asivltgn.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gt2jqdieqvl.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.sweek.top/Article/details/gt2unovvlzh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cqqwz.cn/Article/details/gt2fgdffeug.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.zhijiandao.cn/Article/details/gt2wfucwkzp.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.dianchejie.cn/Article/details/gt2zwokqyfr.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.smart0.xyz/Article/details/gt2wsdtvsav.html

[F03] 写入文件（覆盖）
来源：http://dali.feifeiyinyue.top/Article/details/gt2uhwsscpd.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.smart0.xyz/Article/details/gt2nkypzeqd.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.xylfe.cn/Article/details/gt2kparlrim.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sufxvd.cn/Article/details/gt2wwdosrwl.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.sysykeji.top/Article/details/gt2xiuqqtgx.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.zycfv.cn/Article/details/gt2qikqbvwc.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.yuxming.cn/Article/details/gt2nmizromw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.hnqzz.top/Article/details/gt2imjeaxdv.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2qbxftnql.html

[F04] 追加写入文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdrrmowh.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.zycfv.cn/Article/details/gt2tzmfclqk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.daxiang520.top/Article/details/gt2dfzztesr.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jnjtkalg.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhixingplan.top/Article/details/gt2oytmbsjz.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.zhijiandao.cn/Article/details/gt2mcmyhqvh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.xuetiantiany.cn/Article/details/gt2bmzbexlf.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.guannengcc.top/Article/details/gt2jaiemlsj.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.tian-w.cn/Article/details/gt2bnwccmvy.html

[F05] 判断文件或目录是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gt2vzuxajof.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.fzhhl.top/Article/details/gt2ollgrzma.html

PHP:  file_exists("a.txt");
来源：http://dali.yongpay.top/Article/details/gt2bdprgjbe.html

JS:   fs.existsSync("a.txt")
来源：http://dali.yonumen.top/Article/details/gt2jgzgybpa.html

TS:   fs.existsSync("a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2dcxsypox.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.xziqi.cn/Article/details/gt2pxfysold.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.nwbrower.top/Article/details/gt2pszofxuz.html

Ruby: File.exist?("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2lzagqsrc.html

C#:   File.Exists("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gt2rahxwigo.html

[F06] 删除文件
来源：http://dali.chenlongwang.top/Article/details/gt2gsfgctiw.html

Py:   os.remove("a.txt")
来源：http://dali.gzhubu.top/Article/details/gt2viejmmwu.html

PHP:  unlink("a.txt");
来源：http://dali.chenlongwang.top/Article/details/gt2sogeryci.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.aizwys.cn/Article/details/gt2mupcwndz.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gt2nlnhyxjl.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2revjvboi.html

Go:   os.Remove("a.txt")
来源：http://dali.cheryme.top/Article/details/gt2jcqxguzn.html

Ruby: File.delete("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uelpggpm.html

C#:   File.Delete("a.txt");
来源：http://dali.redwolf501.top/Article/details/gt2osnwrjby.html

[F07] 创建目录（含多级）
来源：http://dali.andypj.xyz/Article/details/gt2dymnfnlv.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.9152youxi.cn/Article/details/gt2pfzmmvre.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.kuanghao11.cn/Article/details/gt2ocnrimou.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.hammf.cn/Article/details/gt2qthjdvhw.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.smart0.xyz/Article/details/gt2qzkowoqo.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xinyue.icu/Article/details/gt2rwbsytqo.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.vqdsnc.cn/Article/details/gt2kwxoglai.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.andypj.xyz/Article/details/gt2lnvesnho.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yuxming.cn/Article/details/gt2flzstqez.html

[F08] 遍历目录
来源：http://dali.zycfv.cn/Article/details/gt2pjwekpjx.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.birdmap.top/Article/details/gt2jxgpjeeb.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.fzhhl.top/Article/details/gt2osvhbgwu.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhixingplan.top/Article/details/gt2mzplmvvs.html

TS:   fs.readdirSync("dir")
来源：http://dali.ybcxt.top/Article/details/gt2vnsqkzmn.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.gotoacloud.top/Article/details/gt2sodccdsh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gt2keapjbag.html

Ruby: Dir.children("dir")
来源：http://dali.fzhhl.top/Article/details/gt2oqmqaele.html

C#:   Directory.GetFiles("dir")
来源：http://dali.mhx1999.top/Article/details/gt2ijhpwqgk.html

[F09] 获取文件大小
来源：http://dali.cashguo.top/Article/details/gt2bgpgcgao.html

Py:   os.path.getsize("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2hlzhgrsm.html

PHP:  filesize("a.txt");
来源：http://dali.yueranfly.top/Article/details/gt2jqckgnir.html

JS:   fs.statSync("a.txt").size
来源：http://dali.chenjidiqi.icu/Article/details/gt2jnsfnqwh.html

TS:   fs.statSync("a.txt").size
来源：http://dali.ydzc1.top/Article/details/gt2xdxdlrpk.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.jinqigufen.top/Article/details/gt2xyvixtwv.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hywenlv.cn/Article/details/gt2gvegvawp.html

Ruby: File.size("a.txt")
来源：http://dali.0kj1m.cn/Article/details/gt2gloztonw.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.dashuyun.cn/Article/details/gt2mmqbsjwr.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yj20258.top/Article/details/gt2essnllvx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.tanke756.top/Article/details/gt2svyjaqcz.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.kuanghao11.cn/Article/details/gt2hcmqndfp.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.316326.xyz/Article/details/gt2drgxrbhc.html

TS:   path.extname("a.txt")
来源：http://dali.jinqigufen.top/Article/details/gt2bfmdlwgx.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.cucudq.cn/Article/details/gt2jnudhfzg.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.cheryme.top/Article/details/gt2seymvviw.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2vrclhgxx.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2xnpjspth.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2kphqjnci.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.316326.xyz/Article/details/gt2qsurgbap.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.haohaochexian.top/Article/details/gt2tlhbfkbd.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.xylfe.cn/Article/details/gt2tincvmhm.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yj20258.top/Article/details/gt2evxzridn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aywdpxsu.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhijiandao.cn/Article/details/gt2vofxgest.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.quarkkingdee.top/Article/details/gt2eohfqwhn.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.sufxvd.cn/Article/details/gt2zaqhrvzv.html

[F12] CSV 读写
来源：http://dali.yj202588.top/Article/details/gt2qqwifhjj.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.sweek.top/Article/details/gt2gwallsmg.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.cucudq.cn/Article/details/gt2svdcdhug.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.haohaochexian.top/Article/details/gt2lrswtwme.html

TS:   // 同上
来源：http://dali.redwolf501.top/Article/details/gt2civtbmgw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.hammf.cn/Article/details/gt2rwgxavor.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2rurfpksf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zhixingplan.top/Article/details/gt2yzokxhxf.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.pycfn.com/Article/details/gt2swiesizt.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2qpqqzfuc.html

G. 面向对象
来源：http://dali.zycfv.cn/Article/details/gt2cswspyga.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gt2kghglnlh.html

[G01] 定义类
来源：http://dali.snrcjt.cn/Article/details/gt2toocdypr.html

Py:   class User: pass
来源：http://dali.yanxiufei.cn/Article/details/gt2xxnnubwp.html

PHP:  class User {}
来源：http://dali.mhx1999.top/Article/details/gt2pagxpufq.html

JS:   class User {}
来源：http://dali.hnxiangtu.top/Article/details/gt2tpualfqa.html

TS:   class User { name: string = ""; }
来源：http://dali.birdmap.top/Article/details/gt2iqlhbmmk.html

Java: class User {}
来源：http://dali.guannengcc.top/Article/details/gt2ksspkkxm.html

Go:   type User struct { Name string }
来源：http://dali.kuanghao11.cn/Article/details/gt2atowpruu.html

Ruby: class User; end
来源：http://dali.0kj1m.cn/Article/details/gt2szsvavvk.html

C#:   class User {}
来源：http://dali.guannengcc.top/Article/details/gt2svmskjdh.html

[G02] 构造函数
来源：http://dali.zhoulong.xyz/Article/details/gt2ulrjmipy.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yanxiufei.cn/Article/details/gt2isjupplv.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.ybcxt.top/Article/details/gt2zuutbuql.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.guowangkeji.top/Article/details/gt2nghzeuby.html

TS:   constructor(public name: string) {}
来源：http://dali.tanke756.top/Article/details/gt2mdgdxntp.html

Java: User(String name) { this.name = name; }
来源：http://dali.birdmap.top/Article/details/gt2wdjjdqay.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.ivvv.top/Article/details/gt2jjongwde.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.pengpengdd.cyou/Article/details/gt2asubsykm.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2twwbpila.html

[G03] 实例属性
来源：http://dali.jqgfzy.top/Article/details/gt2elfexjvr.html

Py:   self.name = "x"
来源：http://dali.gotoacloud.top/Article/details/gt2gaoosbzn.html

PHP:  public string $name = "x";
来源：http://dali.yj20258888.top/Article/details/gt2brlzlrre.html

JS:   this.name = "x";
来源：http://dali.zhongyouzk.top/Article/details/gt2rxskvxxa.html

TS:   name: string = "x";
来源：http://dali.fzhhl.top/Article/details/gt2cnuxhxge.html

Java: private String name;
来源：http://dali.ivvv.top/Article/details/gt2uobkpjch.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.yj202588.top/Article/details/gt2tfcvhvao.html

Ruby: @name = "x"
来源：http://dali.feifeiyinyue.top/Article/details/gt2yeyeadgb.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.aibaodan.cn/Article/details/gt2dfgawgpg.html

[G04] 定义方法
来源：http://dali.jinqigfzy.top/Article/details/gt2idixdxnp.html

Py:   def greet(self): return self.name
来源：http://dali.smart0.xyz/Article/details/gt2stwxmsos.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.bjfxy.top/Article/details/gt2yefsazpa.html

JS:   greet() { return this.name; }
来源：http://dali.316326.xyz/Article/details/gt2yqkelgcl.html

TS:   greet(): string { return this.name; }
来源：http://dali.xinyue.icu/Article/details/gt2gufhhtob.html

Java: String greet() { return name; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2jqmyajzh.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.tanke756.top/Article/details/gt2qqvrgpgl.html

Ruby: def greet; @name; end
来源：http://dali.shuidangran.top/Article/details/gt2kxkxzoyq.html

C#:   public string Greet() => Name;
来源：http://dali.zhengqikj.top/Article/details/gt2sdgbmzzl.html

[G05] 继承
来源：http://dali.gaohongyu789.top/Article/details/gt2mwqqwwbd.html

Py:   class Admin(User): pass
来源：http://dali.ydzc1.top/Article/details/gt2vrsenzvp.html

PHP:  class Admin extends User {}
来源：http://dali.jqgfzy.top/Article/details/gt2dqalmnpj.html

JS:   class Admin extends User {}
来源：http://dali.yonumen.top/Article/details/gt2ljdmansi.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2kbzqhtss.html

Java: class Admin extends User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tlsvphca.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.hysaishi.cn/Article/details/gt2fxlryaqx.html

Ruby: class Admin < User; end
来源：http://dali.gaohongyu789.top/Article/details/gt2tcbfakbi.html

C#:   class Admin : User {}
来源：http://dali.yuanzhike.top/Article/details/gt2mvkxbpsk.html

[G06] 重写方法
来源：http://dali.yongpay.top/Article/details/gt2hogqnlgv.html

Py:   def greet(self): return "admin"
来源：http://dali.shangyingyoupin.top/Article/details/gt2inkesfjn.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.smart0.xyz/Article/details/gt2lwooraqi.html

JS:   greet() { return "admin"; }
来源：http://dali.pengpengdd.cyou/Article/details/gt2qajogjug.html

TS:   greet(): string { return "admin"; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ssmgzjsy.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.dianchejie.cn/Article/details/gt2utinnumn.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yj20258888.top/Article/details/gt2jnvdbrbr.html

Ruby: def greet; "admin"; end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qyyiulnm.html

C#:   public override string Greet() => "admin";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wgfhclaj.html

[G07] 调用父类方法
来源：http://dali.yangfankeji.com/Article/details/gt2kyqbgzjb.html

Py:   super().greet()
来源：http://dali.zhoulong.xyz/Article/details/gt2numuszel.html

PHP:  parent::greet();
来源：http://dali.gogol.net.cn/Article/details/gt2ojwahmey.html

JS:   super.greet();
来源：http://dali.hywenlv.cn/Article/details/gt2mhrhgwfu.html

TS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2cheeisqb.html

Java: super.greet();
来源：http://dali.ppjwa.cn/Article/details/gt2vkwnrail.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.pycfn.com/Article/details/gt2sgufdjic.html

Ruby: super
来源：http://dali.jqgufenzy.top/Article/details/gt2iwuefgri.html

C#:   base.Greet();
来源：http://dali.yvedp.cn/Article/details/gt2ysselpdn.html

[G08] 静态方法与属性
来源：http://dali.haohaochexian.top/Article/details/gt2enyutzpw.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenzaomai.com/Article/details/gt2bsrhphqa.html

PHP:  public static function f() {}
来源：http://dali.ppjwa.cn/Article/details/gt2vhtmvwos.html

JS:   static f() {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2otjrvygt.html

TS:   static f(): void {}
来源：http://dali.316326.xyz/Article/details/gt2pfwrrefe.html

Java: static void f() {}
来源：http://dali.cdnleiting.top/Article/details/gt2gdghjyvn.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.xziqi.cn/Article/details/gt2yavvxnav.html

Ruby: def self.f; end
来源：http://dali.gogol.net.cn/Article/details/gt2rvqhjwiv.html

C#:   public static void F() {}
来源：http://dali.xuetiantiany.cn/Article/details/gt2osszctvl.html

[G09] 接口 / 抽象类
来源：http://dali.316326.xyz/Article/details/gt2wvfgdfrt.html

Py:   from abc import ABC, abstractmethod
来源：http://dali.fzhhl.top/Article/details/gt2qtqzrsay.html

PHP:  interface Shape { public function area(): float; }
来源：http://dali.daria6918.cn/Article/details/gt2zuxilrcu.html

JS:   // 无接口：靠约定或 JSDoc
来源：http://dali.redwolf501.top/Article/details/gt2fjoyquxl.html

TS:   interface Shape { area(): number; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ierbvdsj.html

Java: interface Shape { double area(); }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yrhiakgi.html

Go:   type Shape interface { Area() float64 }
来源：http://dali.iojbl.cn/Article/details/gt2ookwmkqr.html

Ruby: # 无接口：用 module 混入或鸭子类型
来源：http://dali.zhongyouzk.top/Article/details/gt2gzgtwodx.html

C#:   interface IShape { double Area(); }
来源：http://dali.pycfn.com/Article/details/gt2yubigjpw.html

[G10] 访问控制
来源：http://dali.zhiwuduotai.top/Article/details/gt2ubmcmbcf.html

Py:   约定 _protected / __private（不强制）
来源：http://dali.quarkkingdee.top/Article/details/gt2zmswdfvc.html

PHP:  public / protected / private
来源：http://dali.jyoumei.cn/Article/details/gt2nlsvsjix.html

JS:   #private 字段；其余公开
来源：http://dali.0kj1m.cn/Article/details/gt2roankqwu.html

TS:   public / protected / private
来源：http://dali.ehwqpu.com/Article/details/gt2qmxmrnkv.html

Java: public / protected / private / 默认包级
来源：http://dali.quarkkingdee.top/Article/details/gt2wgawogac.html

Go:   首字母大写可导出，小写仅包内可见
来源：http://dali.sweek.top/Article/details/gt2ordafaxs.html

Ruby: public / protected / private
来源：http://dali.birdmap.top/Article/details/gt2juqgsnqw.html

C#:   public / protected / private / internal
来源：http://dali.guowangkeji.top/Article/details/gt2bopvwfnb.html

[G11] getter / setter
来源：http://dali.shzxlz.cn/Article/details/gt2hmyrszqp.html

Py:   @property 与 @x.setter
来源：http://dali.yj20258.top/Article/details/gt2zunxgrjl.html

PHP:  public function getName(): string { return $this->name; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2sbjanyil.html


<!-- 参考信息 -->