代发 wailian999

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.cdnleiting.top/Article/details/gt2vjfjujwv.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.fengsongda.top/Article/details/gt2yyxgmvrq.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.jqgfzy.top/Article/details/gt2iorfoccc.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.shuidangran.top/Article/details/gt2tebfvrsd.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.cqqwz.cn/Article/details/gt2rnlipylp.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.fzhhl.top/Article/details/gt2jtxkboof.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.aizwys.cn/Article/details/gt2dbtgaliw.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.hywenlv.cn/Article/details/gt2pwhmiroo.html

[E10] 左侧补零 / 定长填充
来源：http://dali.hammf.cn/Article/details/gt2unouykcv.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.aizwys.cn/Article/details/gt2twhzjgnx.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gt2bqfwrcdf.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gt2rrtxotmy.html

TS:   "7".padStart(3, "0")
来源：http://dali.chenlongwang.top/Article/details/gt2atjlasbh.html

Java: String.format("%03d", 7)
来源：http://dali.jinqigfzy.top/Article/details/gt2mjtgnozw.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.mhx1999.top/Article/details/gt2lpduwcmo.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.xylfe.cn/Article/details/gt2ypvvhrfl.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.zhongyouzk.top/Article/details/gt2rcjttduz.html

[E11] 反转字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ttzqjayc.html

Py:   s[::-1]
来源：http://dali.yvedp.cn/Article/details/gt2fflthtcm.html

PHP:  strrev($s);
来源：http://dali.cqqwz.cn/Article/details/gt2sjqihuau.html

JS:   [...s].reverse().join("")
来源：http://dali.jinqigufen.top/Article/details/gt2lytenpoq.html

TS:   [...s].reverse().join("")
来源：http://dali.smart0.xyz/Article/details/gt2uxxtmffn.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.jinqigfzy.top/Article/details/gt2xvjchqiy.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.yj20258.top/Article/details/gt2jqwojpgo.html

Ruby: s.reverse
来源：http://dali.chenzaomai.com/Article/details/gt2lrfykjxm.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ehwqpu.com/Article/details/gt2focxiziv.html

[E12] 统计某字符出现次数
来源：http://dali.tian-w.cn/Article/details/gt2nhcojndn.html

Py:   s.count("a")
来源：http://dali.jqgfzy.top/Article/details/gt2dhlyoxyc.html

PHP:  substr_count($s, "a");
来源：http://dali.zhengqikj.top/Article/details/gt2hsrzgiig.html

JS:   s.split("a").length - 1
来源：http://dali.nanxinkj.top/Article/details/gt2kudjtxis.html

TS:   s.split("a").length - 1
来源：http://dali.tian-w.cn/Article/details/gt2jkjngofi.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.xinyue.icu/Article/details/gt2vixswbbm.html

Go:   strings.Count(s, "a")
来源：http://dali.jlsjyb.cn/Article/details/gt2doubclep.html

Ruby: s.count("a")
来源：http://dali.tian-w.cn/Article/details/gt2szkgtwan.html

C#:   s.Count(c => c == 'a')
来源：http://dali.cucudq.cn/Article/details/gt2fpzgmjhw.html

[E13] 逐字符遍历
来源：http://dali.cheryme.top/Article/details/gt2foekmwio.html

Py:   for ch in s: print(ch)
来源：http://dali.xuanzx.com/Article/details/gt2nxsboezq.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.dashuyun.cn/Article/details/gt2tsfvclho.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.iojbl.cn/Article/details/gt2dlqzguvp.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gt2jwrpurqe.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gt2pilpnhme.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yangfankeji.com/Article/details/gt2itdamcsv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hqewjcxy.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.ehwqpu.com/Article/details/gt2xuzeuzjr.html

[E14] URL 编码与 Base64
来源：http://dali.ivvv.top/Article/details/gt2hwdshtks.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fsffenno.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.chenlongwang.top/Article/details/gt2rbsqbmwt.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.yuanzhike.top/Article/details/gt2feglmrdi.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.meibo888.top/Article/details/gt2jelyvkye.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.jinqigfzy.top/Article/details/gt2nvdtnnmy.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhoulong.xyz/Article/details/gt2ucuseemg.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.jinqigufen.top/Article/details/gt2mywgptjy.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.cqqwz.cn/Article/details/gt2tmniulke.html

[E15] HTML 转义 / 反转义
来源：http://dali.chenlongwang.top/Article/details/gt2tuxyufpf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2uzrmiswk.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.shuidangran.top/Article/details/gt2gcmoaqjd.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.gotoacloud.top/Article/details/gt2sfepiyyw.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.shzxlz.cn/Article/details/gt2tzxbrbdt.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.yueranfly.top/Article/details/gt2crhnutrx.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.zhoulong.xyz/Article/details/gt2rykcarhc.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhongyouzk.top/Article/details/gt2zolhxqye.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.nwbrower.top/Article/details/gt2lkmotguf.html

[E16] 数字千分位
来源：http://dali.hammf.cn/Article/details/gt2mzbisozg.html

Py:   f"{1234567:,}"
来源：http://dali.xylfe.cn/Article/details/gt2ncbgiebe.html

PHP:  number_format(1234567);
来源：http://dali.yvedp.cn/Article/details/gt2ghsmjnsf.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.9152youxi.cn/Article/details/gt2phcdsede.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.cucudq.cn/Article/details/gt2onocebbq.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.hongshengwenyu.top/Article/details/gt2wxykrzuy.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.xuanzx.com/Article/details/gt2mobhatog.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.cdnleiting.top/Article/details/gt2ebhixkds.html

C#:   1234567.ToString("N0")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zelayaeg.html

[E17] 首字母大写
来源：http://dali.hnqzz.top/Article/details/gt2uivqxxhl.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.tanke756.top/Article/details/gt2qiegwgyf.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.andypj.xyz/Article/details/gt2bgfbvrou.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.zhengqikj.top/Article/details/gt2mslqpwlk.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.xylfe.cn/Article/details/gt2zntilasf.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cdnleiting.top/Article/details/gt2izslvsbm.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.gaohongyu789.top/Article/details/gt2lcseuvhl.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gt2qivubyjj.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.dashuyun.cn/Article/details/gt2pwzcimff.html

[E18] 模板占位符替换
来源：http://dali.yueranfly.top/Article/details/gt2ggegvdns.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.hnqzz.top/Article/details/gt2zpfwdivj.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zdqjudy.top/Article/details/gt2huiuxuhi.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.xinyue.icu/Article/details/gt2yvejflgi.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.9152youxi.cn/Article/details/gt2ftaqllqr.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.aibaodan.cn/Article/details/gt2xkrqurkw.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.hysaishi.cn/Article/details/gt2eddbgewl.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.jqgufenzy.top/Article/details/gt2pbhblcsk.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.cashguo.top/Article/details/gt2ssayceft.html

[E19] 多行文本按行拆分
来源：http://dali.jyoumei.cn/Article/details/gt2dqbcjnma.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gt2jetujiup.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ivvv.top/Article/details/gt2kgtudxvg.html

JS:   s.split(/\r?\n/)
来源：http://dali.gotoacloud.top/Article/details/gt2urijfhbd.html

TS:   s.split(/\r?\n/)
来源：http://dali.sweek.top/Article/details/gt2wrlwvapm.html

Java: s.lines().toList()
来源：http://dali.jinqigfzy.top/Article/details/gt2sqfuiwhn.html

Go:   strings.Split(s, "\n")
来源：http://dali.nwbrower.top/Article/details/gt2pffzblbb.html

Ruby: s.lines
来源：http://dali.9152youxi.cn/Article/details/gt2notmpzdw.html

C#:   s.Split('\n')
来源：http://dali.tanke756.top/Article/details/gt2rnwyqyao.html

[E20] 判断字符串是否为空
来源：http://dali.zhoulong.xyz/Article/details/gt2aktwnsfi.html

Py:   if not s:
来源：http://dali.yueranfly.top/Article/details/gt2medkajwt.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.9152youxi.cn/Article/details/gt2txkjlsyi.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.yvedp.cn/Article/details/gt2cuwzucpl.html

TS:   if (s === "") {}
来源：http://dali.quarkkingdee.top/Article/details/gt2fuegeqph.html

Java: if (s.isEmpty()) {}
来源：http://dali.yuanzhike.top/Article/details/gt2doevitnp.html

Go:   if s == "" {}
来源：http://dali.jyoumei.cn/Article/details/gt2djdouqel.html

Ruby: if s.empty?
来源：http://dali.9152youxi.cn/Article/details/gt2laqgqqws.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.aizwys.cn/Article/details/gt2ueyotkgb.html

[E21] 超长截断加省略号
来源：http://dali.guannengcc.top/Article/details/gt2bcznhffi.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.shzxlz.cn/Article/details/gt2mmyxxhbg.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.bjfxy.top/Article/details/gt2pyoucqxk.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.shuidangran.top/Article/details/gt2etstlpxm.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.meibo888.top/Article/details/gt2ggmsoiqz.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gt2ccpcjvmj.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.xziqi.cn/Article/details/gt2cdnlnmmb.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj202588.top/Article/details/gt2sbtsiawz.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gt2qzhjuceo.html

[E22] 字节长度与字符长度
来源：http://dali.nanxuanxn.top/Article/details/gt2smgmcxgm.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.gaohongyu789.top/Article/details/gt2hhtwgpli.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.hnxiangtu.top/Article/details/gt2sculkftt.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.bjfxy.top/Article/details/gt2bzrzgtiu.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gt2jpdsxanw.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.redwolf501.top/Article/details/gt2syyeidnb.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.havefunace.top/Article/details/gt2tnpgwqmw.html

Ruby: s.bytesize;  s.length
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dcnrockf.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.svipenyu.cn/Article/details/gt2ifufxrpw.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gt2rjejfmwu.html

F. 文件与目录
来源：http://dali.yueranfly.top/Article/details/gt2shopiolk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gt2cociymys.html

[F01] 读取整个文件
来源：http://dali.sweek.top/Article/details/gt2jxdnxfwu.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gzhubu.top/Article/details/gt2vydnqlff.html

PHP:  file_get_contents("a.txt");
来源：http://dali.hongshengwenyu.top/Article/details/gt2qevpogoq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.jinqigufen.top/Article/details/gt2mnhnjqjz.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zqwtdwjz.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.tanke756.top/Article/details/gt2jgaantpt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.quarkkingdee.top/Article/details/gt2yicaxlit.html

Ruby: File.read("a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gt2dbhsjvyi.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwtmhcvu.html

[F02] 逐行读取文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2rsgtecca.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.svipenyu.cn/Article/details/gt2zqaphyao.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.zycfv.cn/Article/details/gt2bylwnugo.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.wangdashe.top/Article/details/gt2kbiesdkq.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gt2eevfeldn.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.cheryme.top/Article/details/gt2sjhlqcly.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.andypj.xyz/Article/details/gt2pxyckhis.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.sysykeji.top/Article/details/gt2bhirqnsa.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.cucudq.cn/Article/details/gt2tusburbw.html

[F03] 写入文件（覆盖）
来源：http://dali.cheryme.top/Article/details/gt2reshyqin.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.zhengqikj.top/Article/details/gt2venvydac.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.quarkkingdee.top/Article/details/gt2fsdrjedu.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.mhx1999.top/Article/details/gt2sdgjjjbv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ivvv.top/Article/details/gt2ieccihed.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.yj20258.top/Article/details/gt2eyzlybad.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.ppjwa.cn/Article/details/gt2mucihqtj.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.sxryk.cn/Article/details/gt2klxyacoq.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.jianghu66.top/Article/details/gt2zrnmgbzs.html

[F04] 追加写入文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ikcutunn.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.yj20258888.top/Article/details/gt2soneiymg.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.xylfe.cn/Article/details/gt2nboniofv.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.tian-w.cn/Article/details/gt2zarqpdiy.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.yj202588.top/Article/details/gt2dxwbynww.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jyoumei.cn/Article/details/gt2kcfzbluh.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gftdrzyx.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.haohaochexian.top/Article/details/gt2qzwclcpm.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.hnqzz.top/Article/details/gt2xkrzlylo.html

[F05] 判断文件或目录是否存在
来源：http://dali.jiagoushi.top/Article/details/gt2qijvtcnv.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.316326.xyz/Article/details/gt2oixgudpa.html

PHP:  file_exists("a.txt");
来源：http://dali.cdnleiting.top/Article/details/gt2fwzjacka.html

JS:   fs.existsSync("a.txt")
来源：http://dali.hammf.cn/Article/details/gt2lyzchqcg.html

TS:   fs.existsSync("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2vmhoncdx.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gaohongyu789.top/Article/details/gt2tyuchscy.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.jiagoushi.top/Article/details/gt2ratlmhqg.html

Ruby: File.exist?("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gt2rxfeduaj.html

C#:   File.Exists("a.txt")
来源：http://dali.yj20258888.top/Article/details/gt2fdketfbo.html

[F06] 删除文件
来源：http://dali.hnqzz.top/Article/details/gt2erwkmwps.html

Py:   os.remove("a.txt")
来源：http://dali.sysykeji.top/Article/details/gt2qunloshi.html

PHP:  unlink("a.txt");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvbhzmiz.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rtiopsuu.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gt2gwwuqdgo.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gt2qrnnpmuf.html

Go:   os.Remove("a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2ffgbeyba.html

Ruby: File.delete("a.txt")
来源：http://dali.jyoumei.cn/Article/details/gt2yzlkydcl.html

C#:   File.Delete("a.txt");
来源：http://dali.ppjwa.cn/Article/details/gt2svhfrjvj.html

[F07] 创建目录（含多级）
来源：http://dali.cqqwz.cn/Article/details/gt2cicbrujl.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.iojbl.cn/Article/details/gt2lgkurpaf.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.yongpay.top/Article/details/gt2vmcvmecz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.dianchejie.cn/Article/details/gt2tkgnjaez.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.mhx1999.top/Article/details/gt2arrgbxyn.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.dashuyun.cn/Article/details/gt2mtwhbvxn.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ppjwa.cn/Article/details/gt2fuiurhob.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.daxiang520.top/Article/details/gt2jggtdffp.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.haohaochexian.top/Article/details/gt2akpcaegy.html

[F08] 遍历目录
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iepzlsmq.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vbpdinmr.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.zhongyouzk.top/Article/details/gt2wpnnxcdg.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gt2dbdbodgc.html

TS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lwbtcndg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yonumen.top/Article/details/gt2ogboecdz.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.0kj1m.cn/Article/details/gt2enqacpxc.html

Ruby: Dir.children("dir")
来源：http://dali.yongpay.top/Article/details/gt2jbtsrvro.html

C#:   Directory.GetFiles("dir")
来源：http://dali.yangfankeji.com/Article/details/gt2vcoatago.html

[F09] 获取文件大小
来源：http://dali.sysykeji.top/Article/details/gt2btvjradt.html

Py:   os.path.getsize("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gt2edqfykbg.html

PHP:  filesize("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gt2niwmsugz.html

JS:   fs.statSync("a.txt").size
来源：http://dali.bjfxy.top/Article/details/gt2vmxsxuag.html

TS:   fs.statSync("a.txt").size
来源：http://dali.snrcjt.cn/Article/details/gt2uzgaohut.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gt2wbghaoei.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.gzhubu.top/Article/details/gt2ptrsbovx.html

Ruby: File.size("a.txt")
来源：http://dali.guannengcc.top/Article/details/gt2qfijuzss.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzrehkjs.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.dianchejie.cn/Article/details/gt2nfsxolvz.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.yangfankeji.com/Article/details/gt2drumnvgx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.cashguo.top/Article/details/gt2faujlgao.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.ydzc1.top/Article/details/gt2adoiohlv.html

TS:   path.extname("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ovummzet.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.yonumen.top/Article/details/gt2pujrdjwq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.9152youxi.cn/Article/details/gt2cttmjvgr.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.smart0.xyz/Article/details/gt2ykxbnoys.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.yj202588.top/Article/details/gt2odiavfbd.html

[F11] 复制与移动文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2hglfuzwh.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.hysaishi.cn/Article/details/gt2bteqzlrj.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.fengsongda.top/Article/details/gt2skjfmava.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenlongwang.top/Article/details/gt2qtuxgfpp.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.nanxinkj.top/Article/details/gt2fedknsgq.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.chenlongwang.top/Article/details/gt2adezeqzn.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.quarkkingdee.top/Article/details/gt2fbllnext.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.hnqzz.top/Article/details/gt2nqpqotbt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.gogol.net.cn/Article/details/gt2nfxoflwm.html

[F12] CSV 读写
来源：http://dali.zhengqikj.top/Article/details/gt2yocwaeba.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.hnxiangtu.top/Article/details/gt2jqiuoghn.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.hfpthk.cn/Article/details/gt2tnptdoax.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.wangshuangyany.cn/Article/details/gt2glqnzquv.html

TS:   // 同上
来源：http://dali.shuidangran.top/Article/details/gt2kjpweqez.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.9152youxi.cn/Article/details/gt2trucxyhz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.guannengcc.top/Article/details/gt2gducvthy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.zdqjudy.top/Article/details/gt2hcsmatga.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.hnxiangtu.top/Article/details/gt2sprhwjjt.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2kyqqdjjt.html

G. 面向对象
来源：http://dali.yonumen.top/Article/details/gt2klpecqnz.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2stmudlnz.html

[G01] 定义类
来源：http://dali.hywenlv.cn/Article/details/gt2hzkppnvu.html

Py:   class User: pass
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xftqosqj.html

PHP:  class User {}
来源：http://dali.wangshuangyany.cn/Article/details/gt2tmpwtiiw.html

JS:   class User {}
来源：http://dali.xinyue.icu/Article/details/gt2pfrpqskr.html

TS:   class User { name: string = ""; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2eparvger.html

Java: class User {}
来源：http://dali.gotoacloud.top/Article/details/gt2ulcyonsq.html

Go:   type User struct { Name string }
来源：http://dali.cqqwz.cn/Article/details/gt2cfsygkjj.html

Ruby: class User; end
来源：http://dali.dianchejie.cn/Article/details/gt2teffldrh.html

C#:   class User {}
来源：http://dali.nwbrower.top/Article/details/gt2feugxpnd.html

[G02] 构造函数
来源：http://dali.yangfankeji.com/Article/details/gt2zocbuvti.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.zhengqikj.top/Article/details/gt2glnsfqia.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kjlytqiz.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.fengsongda.top/Article/details/gt2bdhtceql.html

TS:   constructor(public name: string) {}
来源：http://dali.zycfv.cn/Article/details/gt2zszdpkuh.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tffclbok.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xuanzx.com/Article/details/gt2bxainklh.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.jyoumei.cn/Article/details/gt2szywuxve.html

C#:   public User(string name) { Name = name; }
来源：http://dali.yj20258888.top/Article/details/gt2bdswnamw.html

[G03] 实例属性
来源：http://dali.fzhhl.top/Article/details/gt2lozrvqow.html

Py:   self.name = "x"
来源：http://dali.bjfxy.top/Article/details/gt2uvwtypir.html

PHP:  public string $name = "x";
来源：http://dali.hammf.cn/Article/details/gt2txhaiaxq.html

JS:   this.name = "x";
来源：http://dali.nwbrower.top/Article/details/gt2yucqzibl.html

TS:   name: string = "x";
来源：http://dali.zhixingplan.top/Article/details/gt2civfddpa.html

Java: private String name;
来源：http://dali.mhx1999.top/Article/details/gt2hqkvppif.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.birdmap.top/Article/details/gt2rfgclmgf.html

Ruby: @name = "x"
来源：http://dali.zdqjudy.top/Article/details/gt2wmnxafcd.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yj20258.top/Article/details/gt2aoynnwni.html

[G04] 定义方法
来源：http://dali.snrcjt.cn/Article/details/gt2rtfzfcyr.html

Py:   def greet(self): return self.name
来源：http://dali.jyoumei.cn/Article/details/gt2mvpibpgo.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhengqikj.top/Article/details/gt2lniioacv.html

JS:   greet() { return this.name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gazvcdcf.html

TS:   greet(): string { return this.name; }
来源：http://dali.nwbrower.top/Article/details/gt2yvzglypj.html

Java: String greet() { return name; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jlzuibku.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2llomelvf.html

Ruby: def greet; @name; end
来源：http://dali.jqgufenzy.top/Article/details/gt2qgknicoy.html

C#:   public string Greet() => Name;
来源：http://dali.haohaochexian.top/Article/details/gt2briznymy.html

[G05] 继承
来源：http://dali.yvedp.cn/Article/details/gt2msjmamxc.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gt2ypkdogty.html

PHP:  class Admin extends User {}
来源：http://dali.smart0.xyz/Article/details/gt2mlzokaac.html

JS:   class Admin extends User {}
来源：http://dali.jianghu66.top/Article/details/gt2oukfsxmw.html

TS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gt2qelwnylb.html

Java: class Admin extends User {}
来源：http://dali.yueranfly.top/Article/details/gt2swkcgsnp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.havefunace.top/Article/details/gt2fcadwqmv.html

Ruby: class Admin < User; end
来源：http://dali.xinyue.icu/Article/details/gt2ciehnefq.html

C#:   class Admin : User {}
来源：http://dali.yuxming.cn/Article/details/gt2fmifjnjb.html

[G06] 重写方法
来源：http://dali.cashguo.top/Article/details/gt2fnxgjxnx.html

Py:   def greet(self): return "admin"
来源：http://dali.snrcjt.cn/Article/details/gt2vnkugsef.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gt2gzalqnvn.html

JS:   greet() { return "admin"; }
来源：http://dali.hnqzz.top/Article/details/gt2rpvslmnj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.hammf.cn/Article/details/gt2gnixpfgr.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.xuetiantiany.cn/Article/details/gt2hyjotphj.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.gaohongyu789.top/Article/details/gt2qqentegc.html

Ruby: def greet; "admin"; end
来源：http://dali.9152youxi.cn/Article/details/gt2ukwiptnk.html

C#:   public override string Greet() => "admin";
来源：http://dali.yj20258.top/Article/details/gt2yuvbawut.html

[G07] 调用父类方法
来源：http://dali.jiagoushi.top/Article/details/gt2myghdywj.html

Py:   super().greet()
来源：http://dali.feifeiyinyue.top/Article/details/gt2rvmoozoy.html

PHP:  parent::greet();
来源：http://dali.cdnleiting.top/Article/details/gt2dtwvzzld.html

JS:   super.greet();
来源：http://dali.yongpay.top/Article/details/gt2xjrppzwf.html

TS:   super.greet();
来源：http://dali.jqgufenzy.top/Article/details/gt2okhkigjz.html

Java: super.greet();
来源：http://dali.wangdashe.top/Article/details/gt2nirogzko.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.zhijiandao.cn/Article/details/gt2iabmsavc.html


<!-- 参考信息 -->