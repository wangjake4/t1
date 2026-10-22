代发 wailian999

[E10] 左侧补零 / 定长填充
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwiaziku.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.ybcxt.top/Article/details/gtjlzhdfsw.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.tanke756.top/Article/details/gtzaxqfoeg.html

JS:   "7".padStart(3, "0")
来源：http://dali.yongpay.top/Article/details/gtsezqscvx.html

TS:   "7".padStart(3, "0")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtazsuzkar.html

Java: String.format("%03d", 7)
来源：http://dali.jianghu66.top/Article/details/gtcwpssybr.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgfoqxofk.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.haohaochexian.top/Article/details/gteevuonlh.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.yueranfly.top/Article/details/gtxosiezox.html

[E11] 反转字符串
来源：http://dali.zhengqikj.top/Article/details/gtyohdruou.html

Py:   s[::-1]
来源：http://dali.jyoumei.cn/Article/details/gtgoraeytz.html

PHP:  strrev($s);
来源：http://dali.sysykeji.top/Article/details/gtyjxjvaxm.html

JS:   [...s].reverse().join("")
来源：http://dali.yangfankeji.com/Article/details/gtkzcdiibf.html

TS:   [...s].reverse().join("")
来源：http://dali.tian-w.cn/Article/details/gtdorxwnap.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.shangyingyoupin.top/Article/details/gtysjyuqlx.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.hywenlv.cn/Article/details/gtwbbbvjuq.html

Ruby: s.reverse
来源：http://dali.hywenlv.cn/Article/details/gteacdowpv.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.vqdsnc.cn/Article/details/gtoziyabnf.html

[E12] 统计某字符出现次数
来源：http://dali.yongpay.top/Article/details/gtilctctrt.html

Py:   s.count("a")
来源：http://dali.hongshengwenyu.top/Article/details/gttbrzgagx.html

PHP:  substr_count($s, "a");
来源：http://dali.pengpengdd.cyou/Article/details/gttbppsddb.html

JS:   s.split("a").length - 1
来源：http://dali.aibaodan.cn/Article/details/gtdrmlosud.html

TS:   s.split("a").length - 1
来源：http://dali.cdnleiting.top/Article/details/gtvxytmjmb.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.jinqigufen.top/Article/details/gtqacqpgsp.html

Go:   strings.Count(s, "a")
来源：http://dali.svipenyu.cn/Article/details/gttycsigoi.html

Ruby: s.count("a")
来源：http://dali.sufxvd.cn/Article/details/gtqmqjdbrj.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtdcmrktjo.html

[E13] 逐字符遍历
来源：http://dali.yj202588.top/Article/details/gtqmysjeep.html

Py:   for ch in s: print(ch)
来源：http://dali.gogol.net.cn/Article/details/gttqrltbjy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteuzcwntn.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.hywenlv.cn/Article/details/gtrzkdadap.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.nanxuanxn.top/Article/details/gtwzcsjqjr.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.xziqi.cn/Article/details/gtiujnqcon.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.chenlongwang.top/Article/details/gtvcxgrlbt.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.fzhhl.top/Article/details/gtzykddqbz.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.quarkkingdee.top/Article/details/gtxokpvutl.html

[E14] URL 编码与 Base64
来源：http://dali.hammf.cn/Article/details/gtrjvpylwq.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.gzhubu.top/Article/details/gthmipyscv.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.hfpthk.cn/Article/details/gtyomynghq.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.zhongyouzk.top/Article/details/gtdtvskjai.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.ehwqpu.com/Article/details/gtgubrwrjh.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.nwbrower.top/Article/details/gtfbkhchta.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.zhengqikj.top/Article/details/gtjpmmmhbl.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.redwolf501.top/Article/details/gtebdtgofj.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqcbhxnq.html

[E15] HTML 转义 / 反转义
来源：http://dali.bjfxy.top/Article/details/gtuwgbytyf.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.snrcjt.cn/Article/details/gtgmgztjqt.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.daxiang520.top/Article/details/gtufglydmi.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.sweek.top/Article/details/gtxebogggh.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.kuanghao11.cn/Article/details/gtmidghxmb.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjfjzlzbi.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.yueranfly.top/Article/details/gtiuxpvgvx.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.yueranfly.top/Article/details/gtoazbarem.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtylsmnaob.html

[E16] 数字千分位
来源：http://dali.ivvv.top/Article/details/gtllmvmyvl.html

Py:   f"{1234567:,}"
来源：http://dali.cucudq.cn/Article/details/gthoeaqadh.html

PHP:  number_format(1234567);
来源：http://dali.jinqigfzy.top/Article/details/gtggwawwru.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.chenlongwang.top/Article/details/gtcfhnqmun.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.yj202588.top/Article/details/gtbvfoiuvg.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.haohaochexian.top/Article/details/gtswndofoe.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.jinghuilouyu.cn/Article/details/gtidgtnsnp.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.yuxming.cn/Article/details/gtyfnpssyz.html

C#:   1234567.ToString("N0")
来源：http://dali.yuanzhike.top/Article/details/gtsjzfqnqm.html

[E17] 首字母大写
来源：http://dali.jiagoushi.top/Article/details/gtbxkxyzbr.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrphimekd.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.shzxlz.cn/Article/details/gtzxyeutps.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtffygcnyo.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.yuxming.cn/Article/details/gtfamfqnkx.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.sysykeji.top/Article/details/gtegtaehtx.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.jyoumei.cn/Article/details/gtwspthrxz.html

Ruby: s.capitalize
来源：http://dali.zhengqikj.top/Article/details/gthoxfeqqv.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpwgwtghh.html

[E18] 模板占位符替换
来源：http://dali.dianchejie.cn/Article/details/gtqfrvxrvy.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.ppjwa.cn/Article/details/gtnfxslmzq.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.jqgufenzy.top/Article/details/gtsmbekmyt.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.nanxinkj.top/Article/details/gtwmhfmfdp.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.sxryk.cn/Article/details/gtcifmawim.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.nanxuanxn.top/Article/details/gtabpdzvix.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.dashuyun.cn/Article/details/gtchfgtllj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.cheryme.top/Article/details/gtfialexce.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.jiagoushi.top/Article/details/gtihshnqlr.html

[E19] 多行文本按行拆分
来源：http://dali.ehwqpu.com/Article/details/gtjlfjcdaf.html

Py:   s.splitlines()
来源：http://dali.gzhubu.top/Article/details/gtwbaexlhy.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.zhixingplan.top/Article/details/gtfhrtdcux.html

JS:   s.split(/\r?\n/)
来源：http://dali.birdmap.top/Article/details/gtchxpsnvo.html

TS:   s.split(/\r?\n/)
来源：http://dali.cqqwz.cn/Article/details/gthubpvxtf.html

Java: s.lines().toList()
来源：http://dali.pycfn.com/Article/details/gtcluppbyb.html

Go:   strings.Split(s, "\n")
来源：http://dali.shuidangran.top/Article/details/gthtccaqar.html

Ruby: s.lines
来源：http://dali.redwolf501.top/Article/details/gtfgoexsft.html

C#:   s.Split('\n')
来源：http://dali.ehwqpu.com/Article/details/gtjxzozhhw.html

[E20] 判断字符串是否为空
来源：http://dali.cucudq.cn/Article/details/gttnwmixys.html

Py:   if not s:
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqffwyqzb.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.xuanzx.com/Article/details/gtvcrojhee.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.ydzc1.top/Article/details/gtlaudrbvb.html

TS:   if (s === "") {}
来源：http://dali.ivvv.top/Article/details/gtaiyyqwsa.html

Java: if (s.isEmpty()) {}
来源：http://dali.shangyingyoupin.top/Article/details/gtmazbedlx.html

Go:   if s == "" {}
来源：http://dali.cheryme.top/Article/details/gtzhymfxmz.html

Ruby: if s.empty?
来源：http://dali.cucudq.cn/Article/details/gtbradbjkp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.yuxming.cn/Article/details/gtikweovhp.html

[E21] 超长截断加省略号
来源：http://dali.tian-w.cn/Article/details/gthbjxwkul.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.redwolf501.top/Article/details/gtptauxpva.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.tian-w.cn/Article/details/gthmitmniy.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.zycfv.cn/Article/details/gtiuluxugq.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.9152youxi.cn/Article/details/gthzgwielq.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.havefunace.top/Article/details/gtqvdiepad.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.havefunace.top/Article/details/gttksgptop.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.zhongyouzk.top/Article/details/gtjfcfhowm.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.quarkkingdee.top/Article/details/gtiunhxsdd.html

[E22] 字节长度与字符长度
来源：http://dali.hongshengwenyu.top/Article/details/gtzbmzwiwp.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.sxryk.cn/Article/details/gtfhtrlqjg.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.kuanghao11.cn/Article/details/gtcvznjqlw.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.chenjidiqi.icu/Article/details/gtkoggwthi.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.yuxming.cn/Article/details/gtagznbffl.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.xuetiantiany.cn/Article/details/gtqnyyfhvn.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.xylfe.cn/Article/details/gtolbgzchn.html

Ruby: s.bytesize;  s.length
来源：http://dali.ehwqpu.com/Article/details/gtlyrqpczs.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.jinghuilouyu.cn/Article/details/gtthnhrsig.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtavmtujbp.html

F. 文件与目录
来源：http://dali.wangdashe.top/Article/details/gtakysbsds.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtbbmxerux.html

[F01] 读取整个文件
来源：http://dali.chenlongwang.top/Article/details/gtkcdptohh.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.cheryme.top/Article/details/gtvbekrlhx.html

PHP:  file_get_contents("a.txt");
来源：http://dali.ivvv.top/Article/details/gtikmuswks.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.yongpay.top/Article/details/gtzdbmmdqm.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.quarkkingdee.top/Article/details/gtsetrnuiv.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.hnqzz.top/Article/details/gtftrtuvvt.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdgmujhka.html

Ruby: File.read("a.txt")
来源：http://dali.yj20258.top/Article/details/gtypgvfcrs.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.quarkkingdee.top/Article/details/gtnbumgyrd.html

[F02] 逐行读取文件
来源：http://dali.dashuyun.cn/Article/details/gtssdbboxt.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.tanke756.top/Article/details/gtyudpewhg.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.gzhubu.top/Article/details/gtnzzbpdjh.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.dashuyun.cn/Article/details/gtuvvpaqdz.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrtzgxug.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.0kj1m.cn/Article/details/gtfoqodaqz.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.c1oappe.top/Article/details/gtrtknvqls.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.hnqzz.top/Article/details/gtthkbcjwe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.hnxiangtu.top/Article/details/gtrpzslrpx.html

[F03] 写入文件（覆盖）
来源：http://dali.pycfn.com/Article/details/gtpndtgont.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnymresyw.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.yvedp.cn/Article/details/gtvzqtppiq.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtqfejlkhv.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.nanxinkj.top/Article/details/gtiijgvdpn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.aizwys.cn/Article/details/gtmoajifud.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.smart0.xyz/Article/details/gtamcbbjju.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtprwqhacm.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.hammf.cn/Article/details/gtxiyeznhj.html

[F04] 追加写入文件
来源：http://dali.iojbl.cn/Article/details/gtdtyemnwv.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.aibaodan.cn/Article/details/gtejgvripl.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.9152youxi.cn/Article/details/gthnfhkgsu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigfzy.top/Article/details/gtinipfrpn.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.daxiang520.top/Article/details/gtdrraczzp.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.shzxlz.cn/Article/details/gtoxghwbtg.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.jyoumei.cn/Article/details/gtywqhurbv.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.daxiang520.top/Article/details/gtjviiwhuz.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.jqgufenzy.top/Article/details/gtoulpfjlt.html

[F05] 判断文件或目录是否存在
来源：http://dali.jinqigufen.top/Article/details/gthphfejcr.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.jinghuilouyu.cn/Article/details/gtivwnwgxo.html

PHP:  file_exists("a.txt");
来源：http://dali.zdqjudy.top/Article/details/gtganvkhwg.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ivvv.top/Article/details/gtmhtjlnvy.html

TS:   fs.existsSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtxovysstm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.gzhubu.top/Article/details/gtqdqfidhh.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.hnxiangtu.top/Article/details/gtktbabxrz.html

Ruby: File.exist?("a.txt")
来源：http://dali.nwbrower.top/Article/details/gtdfbndgtd.html

C#:   File.Exists("a.txt")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtetkqhbcz.html

[F06] 删除文件
来源：http://dali.xylfe.cn/Article/details/gtogmvjjkx.html

Py:   os.remove("a.txt")
来源：http://dali.ppjwa.cn/Article/details/gtkeokgyvb.html

PHP:  unlink("a.txt");
来源：http://dali.xziqi.cn/Article/details/gtzgqappsk.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.quarkkingdee.top/Article/details/gtccromkjo.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.jianghu66.top/Article/details/gtkodkfcss.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.iojbl.cn/Article/details/gtpohhctkn.html

Go:   os.Remove("a.txt")
来源：http://dali.jinqigfzy.top/Article/details/gtbcjfzewu.html

Ruby: File.delete("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtfuozpwjl.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtjbgctmzh.html

[F07] 创建目录（含多级）
来源：http://dali.hysaishi.cn/Article/details/gtonrsprrc.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.hywenlv.cn/Article/details/gtqrvshycg.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.pengpengdd.cyou/Article/details/gtenzshjhu.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.gaohongyu789.top/Article/details/gtzczkwnnn.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yj20258.top/Article/details/gtlcnhffvk.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.xuetiantiany.cn/Article/details/gtnqturjrr.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.ivvv.top/Article/details/gtvioywupp.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.feifeiyinyue.top/Article/details/gtfalmzdbr.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jqgufenzy.top/Article/details/gtsjmfgsjs.html

[F08] 遍历目录
来源：http://dali.dianchejie.cn/Article/details/gttvqsnqwl.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.zhixingplan.top/Article/details/gtqajzllut.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.ydzc1.top/Article/details/gtfooytzyc.html

JS:   fs.readdirSync("dir")
来源：http://dali.zhoulong.xyz/Article/details/gtnmutryqa.html

TS:   fs.readdirSync("dir")
来源：http://dali.zhengqikj.top/Article/details/gtrnjhurjl.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.xinyue.icu/Article/details/gtufzsmcei.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.cqqwz.cn/Article/details/gtczuuywyo.html

Ruby: Dir.children("dir")
来源：http://dali.cucudq.cn/Article/details/gtfznevqip.html

C#:   Directory.GetFiles("dir")
来源：http://dali.quarkkingdee.top/Article/details/gtpzwxhpgg.html

[F09] 获取文件大小
来源：http://dali.chenzaomai.com/Article/details/gtbdcpislp.html

Py:   os.path.getsize("a.txt")
来源：http://dali.kuanghao11.cn/Article/details/gtkrqkbepl.html

PHP:  filesize("a.txt");
来源：http://dali.zhixingplan.top/Article/details/gtlgqzbvvd.html

JS:   fs.statSync("a.txt").size
来源：http://dali.zhongyouzk.top/Article/details/gtnyxcufga.html

TS:   fs.statSync("a.txt").size
来源：http://dali.cdnleiting.top/Article/details/gtzxpwndbi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.tian-w.cn/Article/details/gtqfkilcxx.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.xziqi.cn/Article/details/gtwajtbucg.html

Ruby: File.size("a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtjhkuqsxy.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.quarkkingdee.top/Article/details/gtcdezgauq.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.jianghu66.top/Article/details/gtwhfpzrdx.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.aibaodan.cn/Article/details/gtcqinoycm.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtueiqzbsv.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtbhmjjtvs.html

TS:   path.extname("a.txt")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrbktncak.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.sysykeji.top/Article/details/gtfztvzmmh.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.hongshengwenyu.top/Article/details/gtlpuuvnck.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.yj20258.top/Article/details/gtukskepok.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.gotoacloud.top/Article/details/gtlhcbcait.html

[F11] 复制与移动文件
来源：http://dali.daria6918.cn/Article/details/gtfxwrzgfi.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtlrjuvexi.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.jinqigfzy.top/Article/details/gtgtyrulni.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.yvedp.cn/Article/details/gtckfgcpbq.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtddpogzbn.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.zycfv.cn/Article/details/gtkxwaveah.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.yongpay.top/Article/details/gtuuzrllae.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.nwbrower.top/Article/details/gtudbdnhvy.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.jiagoushi.top/Article/details/gtkxtxxvxk.html

[F12] CSV 读写
来源：http://dali.yj20258888.top/Article/details/gtooyipkne.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.haohaochexian.top/Article/details/gtgpiycbae.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.fzhhl.top/Article/details/gtgmpdkrww.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.jiagoushi.top/Article/details/gtlahzpvdt.html

TS:   // 同上
来源：http://dali.yangfankeji.com/Article/details/gteowsbtcb.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.gogol.net.cn/Article/details/gtnlyqwcid.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hysaishi.cn/Article/details/gtlpkmqlvy.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.yvedp.cn/Article/details/gtmqnosocz.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.zhoulong.xyz/Article/details/gtskdjgksg.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtvfijfsvf.html

G. 面向对象
来源：http://dali.ppjwa.cn/Article/details/gtvnuqoyop.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtrakpdilj.html

[G01] 定义类
来源：http://dali.yueranfly.top/Article/details/gtacammarl.html

Py:   class User: pass
来源：http://dali.havefunace.top/Article/details/gtoyosxooa.html

PHP:  class User {}
来源：http://dali.meibo888.top/Article/details/gtuzmqslig.html

JS:   class User {}
来源：http://dali.snrcjt.cn/Article/details/gtupylvplu.html

TS:   class User { name: string = ""; }
来源：http://dali.yonumen.top/Article/details/gtjusofzkv.html

Java: class User {}
来源：http://dali.yuxming.cn/Article/details/gtxpxxuxfv.html

Go:   type User struct { Name string }
来源：http://dali.cheryme.top/Article/details/gtshgmojsm.html

Ruby: class User; end
来源：http://dali.yj20258.top/Article/details/gttjyheevr.html

C#:   class User {}
来源：http://dali.hammf.cn/Article/details/gtfrrmgcno.html

[G02] 构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtjnxbdsyp.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.yvedp.cn/Article/details/gtoooqbvev.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xziqi.cn/Article/details/gtxphwcbwm.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqjcpjxtp.html

TS:   constructor(public name: string) {}
来源：http://dali.zhongyouzk.top/Article/details/gtczkkjlrx.html

Java: User(String name) { this.name = name; }
来源：http://dali.chenzaomai.com/Article/details/gtyoyqddgf.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.cqqwz.cn/Article/details/gtpyohwhru.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.chenlongwang.top/Article/details/gtohhnhawo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.cashguo.top/Article/details/gthrydgmkg.html

[G03] 实例属性
来源：http://dali.jinqigufen.top/Article/details/gtomhazgxv.html

Py:   self.name = "x"
来源：http://dali.dashuyun.cn/Article/details/gtlvruvuyd.html

PHP:  public string $name = "x";
来源：http://dali.meibo888.top/Article/details/gtxqqeoesv.html

JS:   this.name = "x";
来源：http://dali.aizwys.cn/Article/details/gtuvczqrrg.html

TS:   name: string = "x";
来源：http://dali.yanxiufei.cn/Article/details/gtvhosyftd.html

Java: private String name;
来源：http://dali.yangfankeji.com/Article/details/gtiswrsdho.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.ydzc1.top/Article/details/gthgrmxgbp.html

Ruby: @name = "x"
来源：http://dali.sweek.top/Article/details/gtivvctppi.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvetgkiqg.html

[G04] 定义方法
来源：http://dali.zhongyouzk.top/Article/details/gtzpsfqhzy.html

Py:   def greet(self): return self.name
来源：http://dali.xuetiantiany.cn/Article/details/gtfdzvnkqa.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtimyigbtk.html

JS:   greet() { return this.name; }
来源：http://dali.bjfxy.top/Article/details/gtddamddxa.html

TS:   greet(): string { return this.name; }
来源：http://dali.hywenlv.cn/Article/details/gtagbhwhkt.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gthoytgcqv.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.dashuyun.cn/Article/details/gtyvwwubpj.html

Ruby: def greet; @name; end
来源：http://dali.gogol.net.cn/Article/details/gtyybemdap.html

C#:   public string Greet() => Name;
来源：http://dali.chenzaomai.com/Article/details/gtpzmpcdbk.html

[G05] 继承
来源：http://dali.zhongyouzk.top/Article/details/gtkvovuhyt.html

Py:   class Admin(User): pass
来源：http://dali.9152youxi.cn/Article/details/gtudqhukeb.html

PHP:  class Admin extends User {}
来源：http://dali.shanyushiyangkeji.top/Article/details/gtovzjqnkx.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtyniwynqt.html

TS:   class Admin extends User {}
来源：http://dali.zhaomingkeji.xyz/Article/details/gtosugifhl.html

Java: class Admin extends User {}
来源：http://dali.kuanghao11.cn/Article/details/gtjwsztcnp.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.ybcxt.top/Article/details/gtfhkatcuf.html

Ruby: class Admin < User; end
来源：http://dali.9152youxi.cn/Article/details/gtzwdvycrp.html

C#:   class Admin : User {}
来源：http://dali.fzhhl.top/Article/details/gtiffhxejc.html

[G06] 重写方法
来源：http://dali.jqgfzy.top/Article/details/gtyzhholqi.html

Py:   def greet(self): return "admin"
来源：http://dali.daria6918.cn/Article/details/gtjlunvxzi.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.yvedp.cn/Article/details/gtzrityqzc.html

JS:   greet() { return "admin"; }
来源：http://dali.vqdsnc.cn/Article/details/gtizjspkbd.html

TS:   greet(): string { return "admin"; }
来源：http://dali.ehwqpu.com/Article/details/gtjtnputvp.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.wangdashe.top/Article/details/gtkzojjwat.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yuanzhike.top/Article/details/gtkitkcawb.html

Ruby: def greet; "admin"; end
来源：http://dali.aibaodan.cn/Article/details/gtxcrqbewr.html

C#:   public override string Greet() => "admin";
来源：http://dali.sysykeji.top/Article/details/gtgfgejwdz.html

[G07] 调用父类方法
来源：http://dali.birdmap.top/Article/details/gtiftorpgy.html

Py:   super().greet()
来源：http://dali.yj202588.top/Article/details/gtemiayoqa.html

PHP:  parent::greet();
来源：http://dali.zhengqikj.top/Article/details/gtdcswxtah.html

JS:   super.greet();
来源：http://dali.sysykeji.top/Article/details/gtjjtmozyl.html

TS:   super.greet();
来源：http://dali.yj20258888.top/Article/details/gtinhmwgxj.html

Java: super.greet();
来源：http://dali.xuetiantiany.cn/Article/details/gtoveevxyr.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.shuidangran.top/Article/details/gthkuuyrpd.html

Ruby: super
来源：http://dali.hnqzz.top/Article/details/gtzonfswcv.html

C#:   base.Greet();
来源：http://dali.aibaodan.cn/Article/details/gtdvwevmuh.html

[G08] 静态方法与属性
来源：http://dali.hongshengwenyu.top/Article/details/gtsbqtyrql.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.sysykeji.top/Article/details/gtpilelols.html

PHP:  public static function f() {}
来源：http://dali.cucudq.cn/Article/details/gthtpohfyx.html

JS:   static f() {}
来源：http://dali.ivvv.top/Article/details/gtyosrpqub.html

TS:   static f(): void {}
来源：http://dali.snrcjt.cn/Article/details/gtglgiskri.html

Java: static void f() {}
来源：http://dali.zhixingplan.top/Article/details/gtbtvlitnl.html


<!-- 参考信息 -->