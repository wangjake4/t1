代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.nanxuanxn.top/Article/details/gttfvgbusr.html

Java: String.format("%03d", 7)
来源：http://dali.jlsjyb.cn/Article/details/gtrqbpgroo.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnvtfglib.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.nanxuanxn.top/Article/details/gtpxodrqvr.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.hywenlv.cn/Article/details/gtdcdfxpwf.html

[E11] 反转字符串
来源：http://dali.andypj.xyz/Article/details/gthanyscxt.html

Py:   s[::-1]
来源：http://dali.chenzaomai.com/Article/details/gtgwedodaa.html

PHP:  strrev($s);
来源：http://dali.yueranfly.top/Article/details/gtsqtrbobu.html

JS:   [...s].reverse().join("")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrcmtiguw.html

TS:   [...s].reverse().join("")
来源：http://dali.meibo888.top/Article/details/gtzzuozzxl.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.sweek.top/Article/details/gtioqshyjh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.xuanzx.com/Article/details/gtulmqbiqe.html

Ruby: s.reverse
来源：http://dali.ydzc1.top/Article/details/gtpidxmuia.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ppjwa.cn/Article/details/gtsztfgyux.html

[E12] 统计某字符出现次数
来源：http://dali.yueranfly.top/Article/details/gtjwayauyv.html

Py:   s.count("a")
来源：http://dali.yuxming.cn/Article/details/gtxkmoanna.html

PHP:  substr_count($s, "a");
来源：http://dali.sysykeji.top/Article/details/gteszgldgq.html

JS:   s.split("a").length - 1
来源：http://dali.dashuyun.cn/Article/details/gtdfpqsrvw.html

TS:   s.split("a").length - 1
来源：http://dali.c1oappe.top/Article/details/gtyltwijnz.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.sxryk.cn/Article/details/gtlzgquzpo.html

Go:   strings.Count(s, "a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqofbwcj.html

Ruby: s.count("a")
来源：http://dali.fzhhl.top/Article/details/gtdounsrfc.html

C#:   s.Count(c => c == 'a')
来源：http://dali.ydzc1.top/Article/details/gtbiofvpqp.html

[E13] 逐字符遍历
来源：http://dali.sweek.top/Article/details/gtrwuoyjqi.html

Py:   for ch in s: print(ch)
来源：http://dali.sweek.top/Article/details/gtszjdezti.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.nanxinkj.top/Article/details/gtptzxbunt.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.jianghu66.top/Article/details/gtmahoncge.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.havefunace.top/Article/details/gtcndhyvvn.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyapbiaik.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ydzc1.top/Article/details/gteklglmtf.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shangyingyoupin.top/Article/details/gtgrgpqzeq.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.chenjidiqi.icu/Article/details/gtxrhyeyox.html

[E14] URL 编码与 Base64
来源：http://dali.cdnleiting.top/Article/details/gtsfcbdjyu.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.zycfv.cn/Article/details/gtcreidmxw.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.9152youxi.cn/Article/details/gtpdffgedf.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.guannengcc.top/Article/details/gtzfidebaj.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.dianchejie.cn/Article/details/gtswdaixzw.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.daxiang520.top/Article/details/gtnpvhxjey.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.shzxlz.cn/Article/details/gttzpygzkw.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.nanxinkj.top/Article/details/gtviacnmfa.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.yj202588.top/Article/details/gtqkogppxp.html

[E15] HTML 转义 / 反转义
来源：http://dali.andypj.xyz/Article/details/gtsedzjifp.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.c1oappe.top/Article/details/gtpuusoiff.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.gaohongyu789.top/Article/details/gtstcvoruf.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtyfboymnd.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.fzhhl.top/Article/details/gtoyzvlepr.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ppjwa.cn/Article/details/gtpmyknpjt.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoppwysnu.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.zhixingplan.top/Article/details/gtpvqheusm.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.wangdashe.top/Article/details/gtxfzvziip.html

[E16] 数字千分位
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjflkrzig.html

Py:   f"{1234567:,}"
来源：http://dali.smart0.xyz/Article/details/gtiegmxdmh.html

PHP:  number_format(1234567);
来源：http://dali.xylfe.cn/Article/details/gtfpyzfdmu.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.xziqi.cn/Article/details/gtknwxnopr.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.guowangkeji.top/Article/details/gtzdnqmmfo.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.ehwqpu.com/Article/details/gtxfrognvz.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.mhx1999.top/Article/details/gttrpftroz.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tianlin.xyz/Article/details/gttgomtzum.html

C#:   1234567.ToString("N0")
来源：http://dali.jinqigufen.top/Article/details/gtzlezrlxy.html

[E17] 首字母大写
来源：http://dali.nwbrower.top/Article/details/gtdempdjcv.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.snrcjt.cn/Article/details/gtnugzjbqe.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.cdnleiting.top/Article/details/gtmeeikqqo.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.feifeiyinyue.top/Article/details/gtotjybutj.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.pengpengdd.cyou/Article/details/gtauogrrrc.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.cheryme.top/Article/details/gtrjekeycx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.smart0.xyz/Article/details/gtqqieuzmq.html

Ruby: s.capitalize
来源：http://dali.guannengcc.top/Article/details/gtyxbuqnzb.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shangyingyoupin.top/Article/details/gtonswymwm.html

[E18] 模板占位符替换
来源：http://dali.xinyue.icu/Article/details/gtignsatba.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.c1oappe.top/Article/details/gtctdjqkxa.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.hywenlv.cn/Article/details/gtbukexjky.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.cheryme.top/Article/details/gtdntbvcjo.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.wangshuangyany.cn/Article/details/gtsnxwmutp.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.gotoacloud.top/Article/details/gtzidewzdy.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.sweek.top/Article/details/gtpknfeahk.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.gaohongyu789.top/Article/details/gtdxilaeor.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.xziqi.cn/Article/details/gtdhlisnaf.html

[E19] 多行文本按行拆分
来源：http://dali.wangshuangyany.cn/Article/details/gtozxundse.html

Py:   s.splitlines()
来源：http://dali.dashuyun.cn/Article/details/gtbpbxnrzo.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.aibaodan.cn/Article/details/gtscipillz.html

JS:   s.split(/\r?\n/)
来源：http://dali.zhengqikj.top/Article/details/gtufsygglc.html

TS:   s.split(/\r?\n/)
来源：http://dali.chenlongwang.top/Article/details/gtaemijgoq.html

Java: s.lines().toList()
来源：http://dali.snrcjt.cn/Article/details/gtfkpqqioa.html

Go:   strings.Split(s, "\n")
来源：http://dali.hammf.cn/Article/details/gtgijodbuk.html

Ruby: s.lines
来源：http://dali.shangyingyoupin.top/Article/details/gtilrjpkot.html

C#:   s.Split('\n')
来源：http://dali.xylfe.cn/Article/details/gtatjkucub.html

[E20] 判断字符串是否为空
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrqtiqeb.html

Py:   if not s:
来源：http://dali.zhijiandao.cn/Article/details/gtnxikcktu.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.tanke756.top/Article/details/gtfjxxmzup.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xylfe.cn/Article/details/gtznzcbcuj.html

TS:   if (s === "") {}
来源：http://dali.hfpthk.cn/Article/details/gtunqgywkg.html

Java: if (s.isEmpty()) {}
来源：http://dali.gaohongyu789.top/Article/details/gtbszrmwwz.html

Go:   if s == "" {}
来源：http://dali.aizwys.cn/Article/details/gtdtzaprbp.html

Ruby: if s.empty?
来源：http://dali.sxryk.cn/Article/details/gtdmtugwmf.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.cheryme.top/Article/details/gtwownxlhw.html

[E21] 超长截断加省略号
来源：http://dali.redwolf501.top/Article/details/gtiqitjsrr.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.haohaochexian.top/Article/details/gttvbjrhfr.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.yj202588.top/Article/details/gtzhxukysu.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zdqjudy.top/Article/details/gtywoxgcrp.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwywmsem.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcvyohhnl.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.ppjwa.cn/Article/details/gtanawmocm.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yj20258.top/Article/details/gtxclolyaj.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzeevcyx.html

[E22] 字节长度与字符长度
来源：http://dali.jinqigufen.top/Article/details/gttkowcwgu.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtzahgkjcr.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gtykdsecun.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.shuidangran.top/Article/details/gtlszbjcir.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.fzhhl.top/Article/details/gtuozvzdbd.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cucudq.cn/Article/details/gtqmdoqdwe.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.yuxming.cn/Article/details/gtfdygietv.html

Ruby: s.bytesize;  s.length
来源：http://dali.meibo888.top/Article/details/gtqivuifbj.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.sysykeji.top/Article/details/gtlzmjmobj.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtutmnasnl.html

F. 文件与目录
来源：http://dali.iojbl.cn/Article/details/gtbjmhrzfe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtfedfnknk.html

[F01] 读取整个文件
来源：http://dali.pengpengdd.cyou/Article/details/gtdmwwvsiz.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.jinqigfzy.top/Article/details/gtaopoqchv.html

PHP:  file_get_contents("a.txt");
来源：http://dali.cucudq.cn/Article/details/gtwfzkcauq.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sxryk.cn/Article/details/gtbzxpnolb.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gtssvhsrmo.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.vqdsnc.cn/Article/details/gtomokvriz.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.gotoacloud.top/Article/details/gtnwvehxme.html

Ruby: File.read("a.txt")
来源：http://dali.wangshuangyany.cn/Article/details/gtpgtycafb.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.redwolf501.top/Article/details/gtdbvyamjv.html

[F02] 逐行读取文件
来源：http://dali.ehwqpu.com/Article/details/gtbgxihayu.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.vqdsnc.cn/Article/details/gtvbutpdgm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.quarkkingdee.top/Article/details/gtmrnokjzd.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.chenzaomai.com/Article/details/gtdsuqtdrw.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.yongpay.top/Article/details/gtmetgwvzd.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.nanxinkj.top/Article/details/gtudxxlzny.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.wangdashe.top/Article/details/gtyscesfsj.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.chenzaomai.com/Article/details/gtbwpwsxux.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.jinqigfzy.top/Article/details/gtxmbzukxc.html

[F03] 写入文件（覆盖）
来源：http://dali.sysykeji.top/Article/details/gtifbldbei.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.shanyushiyangkeji.top/Article/details/gttxnjmsvv.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.smart0.xyz/Article/details/gthqvyygaw.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.daxiang520.top/Article/details/gtjyfulcfm.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhixingplan.top/Article/details/gthlwgiedq.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.jinqigufen.top/Article/details/gtbkhxqtup.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.xziqi.cn/Article/details/gtsetztcvb.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.guannengcc.top/Article/details/gtnckdjnqc.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.cdnleiting.top/Article/details/gtoftxneho.html

[F04] 追加写入文件
来源：http://dali.hysaishi.cn/Article/details/gtghlbyvdr.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.svipenyu.cn/Article/details/gtvfjbqsas.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.tanke756.top/Article/details/gtjrmledfy.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxunhyfj.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.quarkkingdee.top/Article/details/gtyutxyotq.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.cqqwz.cn/Article/details/gtfswxigfx.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.gaohongyu789.top/Article/details/gtaxvlugjk.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtxdrrptoz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.havefunace.top/Article/details/gtvhsbnecx.html

[F05] 判断文件或目录是否存在
来源：http://dali.hysaishi.cn/Article/details/gtxgtbytme.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.ivvv.top/Article/details/gtokgjdkew.html

PHP:  file_exists("a.txt");
来源：http://dali.ehwqpu.com/Article/details/gtjqrticcv.html

JS:   fs.existsSync("a.txt")
来源：http://dali.feifeiyinyue.top/Article/details/gtbhzmrmpc.html

TS:   fs.existsSync("a.txt")
来源：http://dali.316326.xyz/Article/details/gtwbukuelg.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.nwbrower.top/Article/details/gtmvrhjlsd.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtysqakjwr.html

Ruby: File.exist?("a.txt")
来源：http://dali.shzxlz.cn/Article/details/gtozxwypts.html

C#:   File.Exists("a.txt")
来源：http://dali.haohaochexian.top/Article/details/gtblietzks.html

[F06] 删除文件
来源：http://dali.zhoulong.xyz/Article/details/gtqtxsffde.html

Py:   os.remove("a.txt")
来源：http://dali.havefunace.top/Article/details/gtggdwfnwa.html

PHP:  unlink("a.txt");
来源：http://dali.yuxming.cn/Article/details/gtebxmmtvp.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hfpthk.cn/Article/details/gtsyvldjua.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtvmpnbyfh.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.cashguo.top/Article/details/gtapgqldhj.html

Go:   os.Remove("a.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtjhvrbzuh.html

Ruby: File.delete("a.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtvxtvmntr.html

C#:   File.Delete("a.txt");
来源：http://dali.meibo888.top/Article/details/gtollenaee.html

[F07] 创建目录（含多级）
来源：http://dali.ppjwa.cn/Article/details/gteravzxpw.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hysaishi.cn/Article/details/gtpmlkqejy.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.smart0.xyz/Article/details/gtvyeqlppc.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.iojbl.cn/Article/details/gtplcuxftk.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gogol.net.cn/Article/details/gthjradzlq.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.iojbl.cn/Article/details/gtjjtdyori.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.jlsjyb.cn/Article/details/gtzmrxjkqy.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.yvedp.cn/Article/details/gtaxosxbph.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.hfpthk.cn/Article/details/gtdvjgmlot.html

[F08] 遍历目录
来源：http://dali.kuanghao11.cn/Article/details/gtylmwljeh.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.yj20258.top/Article/details/gtlesppyhf.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.snrcjt.cn/Article/details/gtulytfnod.html

JS:   fs.readdirSync("dir")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthumcsfem.html

TS:   fs.readdirSync("dir")
来源：http://dali.svipenyu.cn/Article/details/gtwaueqsyg.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.wangshuangyany.cn/Article/details/gtamrcyxgo.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cheryme.top/Article/details/gtaixthiue.html

Ruby: Dir.children("dir")
来源：http://dali.jinqigfzy.top/Article/details/gtpomkffqv.html

C#:   Directory.GetFiles("dir")
来源：http://dali.xuetiantiany.cn/Article/details/gtneoufyjc.html

[F09] 获取文件大小
来源：http://dali.bjfxy.top/Article/details/gtspaethhw.html

Py:   os.path.getsize("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtemruhnjn.html

PHP:  filesize("a.txt");
来源：http://dali.xinyue.icu/Article/details/gtpfqralzg.html

JS:   fs.statSync("a.txt").size
来源：http://dali.aizwys.cn/Article/details/gtosdniila.html

TS:   fs.statSync("a.txt").size
来源：http://dali.guowangkeji.top/Article/details/gtxfnbknrh.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.bjfxy.top/Article/details/gtaekuqzdg.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.cdnleiting.top/Article/details/gtkwqqgfzv.html

Ruby: File.size("a.txt")
来源：http://dali.gogol.net.cn/Article/details/gtvkrcpico.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.jiagoushi.top/Article/details/gtofgwioja.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.shuidangran.top/Article/details/gtxqhaqkst.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtdfwlyjmx.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.redwolf501.top/Article/details/gtnsrllfrj.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.xuanzx.com/Article/details/gtzsmxfnwg.html

TS:   path.extname("a.txt")
来源：http://dali.cqqwz.cn/Article/details/gtehgnxole.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.zhixingplan.top/Article/details/gtokxgurvq.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.chenzaomai.com/Article/details/gtiteffdwa.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtbtpvikgg.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.guannengcc.top/Article/details/gtzpbkradu.html

[F11] 复制与移动文件
来源：http://dali.c1oappe.top/Article/details/gthwdnelap.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtfahmlyba.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.quarkkingdee.top/Article/details/gttynkygkk.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.chenjidiqi.icu/Article/details/gtnnbqrgpu.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtnczxpfyr.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.tian-w.cn/Article/details/gtswwvqzuk.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.zhoulong.xyz/Article/details/gtusuzhitu.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.daria6918.cn/Article/details/gtbtajmbjt.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.hnxiangtu.top/Article/details/gtfbntklrx.html

[F12] CSV 读写
来源：http://dali.tianlin.xyz/Article/details/gtqljfnflf.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.xziqi.cn/Article/details/gtujsxdjak.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.yuxming.cn/Article/details/gtqkhijvgl.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.nanxinkj.top/Article/details/gtarwbgcbe.html

TS:   // 同上
来源：http://dali.jqgufenzy.top/Article/details/gttmbdmfng.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.feifeiyinyue.top/Article/details/gtdwfrnehv.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnxiangtu.top/Article/details/gtxyavsbcb.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.mhx1999.top/Article/details/gtzrtrcocl.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdxovgdai.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtxovemmxv.html

G. 面向对象
来源：http://dali.xuanzx.com/Article/details/gtrdcavjaq.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtgrceekkj.html

[G01] 定义类
来源：http://dali.tanke756.top/Article/details/gtcajzdwrh.html

Py:   class User: pass
来源：http://dali.sxryk.cn/Article/details/gtamnqovyq.html

PHP:  class User {}
来源：http://dali.sysykeji.top/Article/details/gtxbjysrlg.html

JS:   class User {}
来源：http://dali.yj20258.top/Article/details/gtrwgfxiew.html

TS:   class User { name: string = ""; }
来源：http://dali.quarkkingdee.top/Article/details/gtaskhenuw.html

Java: class User {}
来源：http://dali.dashuyun.cn/Article/details/gtvaupmqpv.html

Go:   type User struct { Name string }
来源：http://dali.yonumen.top/Article/details/gthdbflqpb.html

Ruby: class User; end
来源：http://dali.hfpthk.cn/Article/details/gtbgvszyee.html

C#:   class User {}
来源：http://dali.feifeiyinyue.top/Article/details/gthnkamdoi.html

[G02] 构造函数
来源：http://dali.nanxuanxn.top/Article/details/gtraewryar.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.tanke756.top/Article/details/gtmnvkepgn.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.feifeiyinyue.top/Article/details/gtzkmajsoo.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zdqjudy.top/Article/details/gtxmgnbwan.html

TS:   constructor(public name: string) {}
来源：http://dali.xziqi.cn/Article/details/gtxjmsbzcx.html

Java: User(String name) { this.name = name; }
来源：http://dali.zhijiandao.cn/Article/details/gtcfbgzpwq.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.xziqi.cn/Article/details/gtwtkmxiik.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.redwolf501.top/Article/details/gttzwruxjx.html

C#:   public User(string name) { Name = name; }
来源：http://dali.hnqzz.top/Article/details/gtkrrfjjul.html

[G03] 实例属性
来源：http://dali.yj20258.top/Article/details/gtxdqpjeun.html

Py:   self.name = "x"
来源：http://dali.sweek.top/Article/details/gtnzgtxkwm.html

PHP:  public string $name = "x";
来源：http://dali.316326.xyz/Article/details/gtcocrxugm.html

JS:   this.name = "x";
来源：http://dali.hysaishi.cn/Article/details/gtqtmihelk.html

TS:   name: string = "x";
来源：http://dali.9152youxi.cn/Article/details/gtsyfjqcvk.html

Java: private String name;
来源：http://dali.iojbl.cn/Article/details/gttbefylck.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.hnxiangtu.top/Article/details/gtiluswogs.html

Ruby: @name = "x"
来源：http://dali.0kj1m.cn/Article/details/gtdocliqrf.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.cqqwz.cn/Article/details/gtpsbthwkt.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtshurlxfd.html

Py:   def greet(self): return self.name
来源：http://dali.cashguo.top/Article/details/gtceaxchuj.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.ppjwa.cn/Article/details/gtcxqpoiiw.html

JS:   greet() { return this.name; }
来源：http://dali.0kj1m.cn/Article/details/gtdprnnwnp.html

TS:   greet(): string { return this.name; }
来源：http://dali.hfpthk.cn/Article/details/gtcwwsorqi.html

Java: String greet() { return name; }
来源：http://dali.0kj1m.cn/Article/details/gtuartnbri.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yj202588.top/Article/details/gtjlpcojxu.html

Ruby: def greet; @name; end
来源：http://dali.hongshengwenyu.top/Article/details/gtfehptbap.html

C#:   public string Greet() => Name;
来源：http://dali.daria6918.cn/Article/details/gtfkoebfvq.html

[G05] 继承
来源：http://dali.yanxiufei.cn/Article/details/gtkcchvswd.html

Py:   class Admin(User): pass
来源：http://dali.0kj1m.cn/Article/details/gtaqptszsk.html

PHP:  class Admin extends User {}
来源：http://dali.xziqi.cn/Article/details/gtzbxtcxlb.html

JS:   class Admin extends User {}
来源：http://dali.cashguo.top/Article/details/gtxqtzqtza.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gtryfkzbml.html

Java: class Admin extends User {}
来源：http://dali.guowangkeji.top/Article/details/gtfoxavtbl.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.jianghu66.top/Article/details/gtbknwsoyu.html

Ruby: class Admin < User; end
来源：http://dali.shanyushiyangtech.top/Article/details/gtlzkneegg.html

C#:   class Admin : User {}
来源：http://dali.wangdashe.top/Article/details/gtyuvvmwuh.html

[G06] 重写方法
来源：http://dali.0kj1m.cn/Article/details/gtunmoifde.html

Py:   def greet(self): return "admin"
来源：http://dali.yj20258888.top/Article/details/gtucrgjebu.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.gogol.net.cn/Article/details/gtyschhabs.html

JS:   greet() { return "admin"; }
来源：http://dali.ivvv.top/Article/details/gtcibndtaz.html

TS:   greet(): string { return "admin"; }
来源：http://dali.nanxuanxn.top/Article/details/gtlfdshrzo.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.zhengqikj.top/Article/details/gttbbfyhfx.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.fzhhl.top/Article/details/gtusxioexd.html

Ruby: def greet; "admin"; end
来源：http://dali.jqgfzy.top/Article/details/gtzofjhuol.html

C#:   public override string Greet() => "admin";
来源：http://dali.tian-w.cn/Article/details/gteynqgxmk.html

[G07] 调用父类方法
来源：http://dali.sxryk.cn/Article/details/gttiurlyfi.html

Py:   super().greet()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqznooduv.html

PHP:  parent::greet();
来源：http://dali.jianghu66.top/Article/details/gtafndbnyu.html

JS:   super.greet();
来源：http://dali.birdmap.top/Article/details/gtjemkzxal.html

TS:   super.greet();
来源：http://dali.mhx1999.top/Article/details/gtypszkthh.html

Java: super.greet();
来源：http://dali.sweek.top/Article/details/gtyisqtnaz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.havefunace.top/Article/details/gtyyzyayjb.html

Ruby: super
来源：http://dali.kuanghao11.cn/Article/details/gttjtgrzkc.html

C#:   base.Greet();
来源：http://dali.shanyushiyangtech.top/Article/details/gtsndbzoka.html

[G08] 静态方法与属性
来源：http://dali.yj20258888.top/Article/details/gtohkmzyxh.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.chenlongwang.top/Article/details/gtbyakjyjm.html

PHP:  public static function f() {}
来源：http://dali.sweek.top/Article/details/gtiamgqoai.html

JS:   static f() {}
来源：http://dali.havefunace.top/Article/details/gtglbtznyy.html

TS:   static f(): void {}
来源：http://dali.hfpthk.cn/Article/details/gtvmwmdwdy.html

Java: static void f() {}
来源：http://dali.hongshengwenyu.top/Article/details/gtzamtfwhj.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.daria6918.cn/Article/details/gtdjdwkfjh.html

Ruby: def self.f; end
来源：http://dali.jinqigufen.top/Article/details/gtuphkyajw.html

C#:   public static void F() {}
来源：http://dali.jinqigufen.top/Article/details/gtfezejqeo.html

[G09] 接口 / 抽象类
来源：http://dali.nwbrower.top/Article/details/gtefbguwnm.html


<!-- 参考信息 -->