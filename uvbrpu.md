代发 wailian999

PHP:  implode(",", $items);
来源：http://dali.jlsjyb.cn/Article/details/gtvecuqujh.html

JS:   items.join(",")
来源：http://dali.redwolf501.top/Article/details/gtaauumddu.html

TS:   items.join(",")
来源：http://dali.yueranfly.top/Article/details/gtzsjxfysu.html

Java: String.join(",", items)
来源：http://dali.jinghuilouyu.cn/Article/details/gtepnxvyps.html

Go:   strings.Join(items, ",")
来源：http://dali.pycfn.com/Article/details/gttwzitgnu.html

Ruby: items.join(",")
来源：http://dali.sweek.top/Article/details/gtbqcbupfk.html

C#:   string.Join(",", items)
来源：http://dali.hongshengwenyu.top/Article/details/gtqdnaddni.html

[E09] 去除所有空白字符
来源：http://dali.9152youxi.cn/Article/details/gtaepaohpi.html

Py:   "".join(s.split());  re.sub(r"\s+", "", s)
来源：http://dali.sweek.top/Article/details/gtdxcxntpo.html

PHP:  preg_replace('/\s+/', '', $s);
来源：http://dali.tanke756.top/Article/details/gthtqptgwp.html

JS:   s.replace(/\s+/g, "")
来源：http://dali.shanyushiyangtech.top/Article/details/gtntxyiybd.html

TS:   s.replace(/\s+/g, "")
来源：http://dali.yj20258888.top/Article/details/gtyqmrcmzq.html

Java: s.replaceAll("\\s+", "")
来源：http://dali.yangfankeji.com/Article/details/gtfjpaasov.html

Go:   strings.Join(strings.Fields(s), "")
来源：http://dali.nanxinkj.top/Article/details/gtdwjclzyz.html

Ruby: s.gsub(/\s+/, "")
来源：http://dali.cashguo.top/Article/details/gtxzsxcvjo.html

C#:   Regex.Replace(s, @"\s+", "")
来源：http://dali.jinqigfzy.top/Article/details/gtaxciztii.html

[E10] 左侧补零 / 定长填充
来源：http://dali.xziqi.cn/Article/details/gtybtvzgsa.html

Py:   str(7).zfill(3);  "7".rjust(3, "0")
来源：http://dali.hnqzz.top/Article/details/gtdyghppud.html

PHP:  str_pad("7", 3, "0", STR_PAD_LEFT);
来源：http://dali.cheryme.top/Article/details/gtcdjkisgz.html

JS:   "7".padStart(3, "0")
来源：http://dali.guowangkeji.top/Article/details/gtcdabsira.html

TS:   "7".padStart(3, "0")
来源：http://dali.yanxiufei.cn/Article/details/gtdppkygxg.html

Java: String.format("%03d", 7)
来源：http://dali.daxiang520.top/Article/details/gtpvyfmgen.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.hammf.cn/Article/details/gtfcoheryp.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.pycfn.com/Article/details/gtarrygfil.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.9152youxi.cn/Article/details/gtjtkggdjq.html

[E11] 反转字符串
来源：http://dali.xuetiantiany.cn/Article/details/gtdwotduhr.html

Py:   s[::-1]
来源：http://dali.cheryme.top/Article/details/gtvpifqoqh.html

PHP:  strrev($s);
来源：http://dali.guowangkeji.top/Article/details/gtpokevtvp.html

JS:   [...s].reverse().join("")
来源：http://dali.zhoulong.xyz/Article/details/gthoaffpcb.html

TS:   [...s].reverse().join("")
来源：http://dali.aizwys.cn/Article/details/gtfqkmxzwh.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.tianlin.xyz/Article/details/gtcpwpngoh.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.chenlongwang.top/Article/details/gtguwylpyc.html

Ruby: s.reverse
来源：http://dali.smart0.xyz/Article/details/gthmctrpbr.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnhhfidiw.html

[E12] 统计某字符出现次数
来源：http://dali.jiagoushi.top/Article/details/gtgqkhxfgp.html

Py:   s.count("a")
来源：http://dali.zhijiandao.cn/Article/details/gtrcgxxfkk.html

PHP:  substr_count($s, "a");
来源：http://dali.aibaodan.cn/Article/details/gtdcpnmbof.html

JS:   s.split("a").length - 1
来源：http://dali.0kj1m.cn/Article/details/gtwfolyaqg.html

TS:   s.split("a").length - 1
来源：http://dali.mhx1999.top/Article/details/gtobofwuqk.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.yonumen.top/Article/details/gtktfmjtcz.html

Go:   strings.Count(s, "a")
来源：http://dali.sufxvd.cn/Article/details/gtqjeyhszc.html

Ruby: s.count("a")
来源：http://dali.yj20258.top/Article/details/gtvygdijxl.html

C#:   s.Count(c => c == 'a')
来源：http://dali.chenlongwang.top/Article/details/gtoxlodtsk.html

[E13] 逐字符遍历
来源：http://dali.yj20258888.top/Article/details/gtqkltwked.html

Py:   for ch in s: print(ch)
来源：http://dali.ivvv.top/Article/details/gtokywjizg.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.hysaishi.cn/Article/details/gtogpnjxuj.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.snrcjt.cn/Article/details/gtwhsqutqq.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.feifeiyinyue.top/Article/details/gtrgbndvux.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.jiagoushi.top/Article/details/gtfdgzyser.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.ppjwa.cn/Article/details/gtoueyqkpr.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.chenzaomai.com/Article/details/gtqihtzcpo.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.zhixingplan.top/Article/details/gtqwsjyahn.html

[E14] URL 编码与 Base64
来源：http://dali.yonumen.top/Article/details/gtpgajsdap.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtxcpmltsd.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.sxryk.cn/Article/details/gtkrwhwizj.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfebonmkn.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtltrfnbuy.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.yj20258888.top/Article/details/gtywyjpjkk.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.hammf.cn/Article/details/gtrhbqqvwi.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.guannengcc.top/Article/details/gtzbjrulng.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtyrsoxffr.html

[E15] HTML 转义 / 反转义
来源：http://dali.smart0.xyz/Article/details/gtpxdqmpyg.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.gotoacloud.top/Article/details/gtytsvjxfl.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.zhiwuduotai.top/Article/details/gtlyivrsue.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.mhx1999.top/Article/details/gtpmvoewet.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.yangfankeji.com/Article/details/gtyopomwlf.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.hfpthk.cn/Article/details/gttjnogzsf.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtqhswvcsh.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.dashuyun.cn/Article/details/gtktudjbmy.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.feifeiyinyue.top/Article/details/gteqlflbgc.html

[E16] 数字千分位
来源：http://dali.zhijiandao.cn/Article/details/gtzqgxinhp.html

Py:   f"{1234567:,}"
来源：http://dali.feifeiyinyue.top/Article/details/gteooqqqdq.html

PHP:  number_format(1234567);
来源：http://dali.bjfxy.top/Article/details/gtttulbmku.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.hfpthk.cn/Article/details/gtwywdylik.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.zhoulong.xyz/Article/details/gtmldlivnl.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.pycfn.com/Article/details/gtrkmizxfv.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.gzhubu.top/Article/details/gtotsiiqxn.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwfgykxce.html

C#:   1234567.ToString("N0")
来源：http://dali.daxiang520.top/Article/details/gtwkcsbxxu.html

[E17] 首字母大写
来源：http://dali.hfpthk.cn/Article/details/gtomndtmad.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.wangshuangyany.cn/Article/details/gtxmdogixa.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.daria6918.cn/Article/details/gtcpdctjcz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.jyoumei.cn/Article/details/gtfuuuewxa.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.kuanghao11.cn/Article/details/gtnivfwjib.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.hnxiangtu.top/Article/details/gtgulhaoqo.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.316326.xyz/Article/details/gtidmcbhai.html

Ruby: s.capitalize
来源：http://dali.jlsjyb.cn/Article/details/gtsrpioqvo.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.zhongyouzk.top/Article/details/gtaokvoqul.html

[E18] 模板占位符替换
来源：http://dali.quarkkingdee.top/Article/details/gtcwunkpgl.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.wangdashe.top/Article/details/gtwtdgmoic.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.0kj1m.cn/Article/details/gtreiauzdn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.yj20258.top/Article/details/gtukdhrjbb.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.cqqwz.cn/Article/details/gtzsdmcpbg.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.zhoulong.xyz/Article/details/gtjqpvjmxj.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.quarkkingdee.top/Article/details/gtwoqdqtcm.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.andypj.xyz/Article/details/gtmmjrximj.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.kuanghao11.cn/Article/details/gtdgudrkwu.html

[E19] 多行文本按行拆分
来源：http://dali.yvedp.cn/Article/details/gtntvqlxlc.html

Py:   s.splitlines()
来源：http://dali.xuanzx.com/Article/details/gtgpggyzkv.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.ybcxt.top/Article/details/gtprrdwrog.html

JS:   s.split(/\r?\n/)
来源：http://dali.hammf.cn/Article/details/gtxrflbkni.html

TS:   s.split(/\r?\n/)
来源：http://dali.hywenlv.cn/Article/details/gtqepvdvbc.html

Java: s.lines().toList()
来源：http://dali.gzhubu.top/Article/details/gtrmewnfdi.html

Go:   strings.Split(s, "\n")
来源：http://dali.bjfxy.top/Article/details/gtwuxoydci.html

Ruby: s.lines
来源：http://dali.nwbrower.top/Article/details/gtsdjyzejx.html

C#:   s.Split('\n')
来源：http://dali.mhx1999.top/Article/details/gtmbxziwnp.html

[E20] 判断字符串是否为空
来源：http://dali.aizwys.cn/Article/details/gtgesxpaxd.html

Py:   if not s:
来源：http://dali.shzxlz.cn/Article/details/gtphylhcab.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.c1oappe.top/Article/details/gtlojboxyz.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.cdnleiting.top/Article/details/gtvkqaswxa.html

TS:   if (s === "") {}
来源：http://dali.nanxinkj.top/Article/details/gtkiralzfl.html

Java: if (s.isEmpty()) {}
来源：http://dali.iojbl.cn/Article/details/gtwnfdlzza.html

Go:   if s == "" {}
来源：http://dali.xziqi.cn/Article/details/gtpmihshws.html

Ruby: if s.empty?
来源：http://dali.yueranfly.top/Article/details/gtrisdpkhc.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.zhoulong.xyz/Article/details/gtqyfnpgut.html

[E21] 超长截断加省略号
来源：http://dali.ppjwa.cn/Article/details/gttzxdlgds.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.zhaomingkeji.xyz/Article/details/gthjutosff.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.gogol.net.cn/Article/details/gtqparlwni.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.xziqi.cn/Article/details/gtmbhtfjrl.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.cheryme.top/Article/details/gtymtqfcxr.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.316326.xyz/Article/details/gtmsbquhkx.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.zhengqikj.top/Article/details/gtvoawxbid.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.yongpay.top/Article/details/gtuyopecjk.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.cheryme.top/Article/details/gtzopwduqd.html

[E22] 字节长度与字符长度
来源：http://dali.dashuyun.cn/Article/details/gtzdlrmowz.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ivvv.top/Article/details/gtctaatvkv.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.jqgufenzy.top/Article/details/gtvpjpjgzb.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.tanke756.top/Article/details/gtepbamczw.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.hongshengwenyu.top/Article/details/gtqpnnxcfp.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.cashguo.top/Article/details/gtlublobci.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.meibo888.top/Article/details/gtgswjeqnd.html

Ruby: s.bytesize;  s.length
来源：http://dali.jlsjyb.cn/Article/details/gtegaeigyy.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.meibo888.top/Article/details/gtshnntncl.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtowexngfg.html

F. 文件与目录
来源：http://dali.jiagoushi.top/Article/details/gtswrqpwoq.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtnftczbhu.html

[F01] 读取整个文件
来源：http://dali.jinqigufen.top/Article/details/gtsogbllqi.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.haohaochexian.top/Article/details/gtullfamui.html

PHP:  file_get_contents("a.txt");
来源：http://dali.sxryk.cn/Article/details/gttzxvxcch.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.sweek.top/Article/details/gtrrsmeqqs.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.hnxiangtu.top/Article/details/gtmhljgjty.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.daxiang520.top/Article/details/gtbktrurib.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.sweek.top/Article/details/gtlhmbzbzh.html

Ruby: File.read("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtpmfdrjvw.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.wangshuangyany.cn/Article/details/gtwvtlahzl.html

[F02] 逐行读取文件
来源：http://dali.jlsjyb.cn/Article/details/gtwufoonca.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.yvedp.cn/Article/details/gtiayxfuhp.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtwgeipqit.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.hnxiangtu.top/Article/details/gttqcjqksr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.gogol.net.cn/Article/details/gtomiwdpdh.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.andypj.xyz/Article/details/gtbbugdpwn.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcdcrlwgn.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.zhongyouzk.top/Article/details/gtzrcpajxh.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.9152youxi.cn/Article/details/gtbgudjngm.html

[F03] 写入文件（覆盖）
来源：http://dali.yj20258888.top/Article/details/gtybbnylyl.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.cheryme.top/Article/details/gtomtbuuhq.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.feifeiyinyue.top/Article/details/gtzeejdidy.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.ydzc1.top/Article/details/gtspgkxsrb.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.zhiwuduotai.top/Article/details/gtrtxkynhn.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.andypj.xyz/Article/details/gtaowtoqtt.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jinqigufen.top/Article/details/gtkhzkdzmi.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.nanxinkj.top/Article/details/gtztuogxhl.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.dashuyun.cn/Article/details/gtnlavqtjj.html

[F04] 追加写入文件
来源：http://dali.pengpengdd.cyou/Article/details/gtaenldgnt.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.shuidangran.top/Article/details/gtvwtplqzk.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.chenlongwang.top/Article/details/gtjpqcxtcb.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsjclbaw.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.andypj.xyz/Article/details/gtbkjkghbj.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.jlsjyb.cn/Article/details/gtymdbhmih.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.wangshuangyany.cn/Article/details/gtgjcdfirg.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.meibo888.top/Article/details/gtdcbytqzy.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cdnleiting.top/Article/details/gtoxeuoisu.html

[F05] 判断文件或目录是否存在
来源：http://dali.0kj1m.cn/Article/details/gtefzxhieg.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.yj20258.top/Article/details/gtpyuhufoq.html

PHP:  file_exists("a.txt");
来源：http://dali.birdmap.top/Article/details/gtpcrlreok.html

JS:   fs.existsSync("a.txt")
来源：http://dali.ybcxt.top/Article/details/gtzdxkgebw.html

TS:   fs.existsSync("a.txt")
来源：http://dali.dianchejie.cn/Article/details/gtbgljpykw.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.aizwys.cn/Article/details/gtnijpwtce.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.cashguo.top/Article/details/gtkiotfwqd.html

Ruby: File.exist?("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtddwwmvnk.html

C#:   File.Exists("a.txt")
来源：http://dali.havefunace.top/Article/details/gthfzubtsl.html

[F06] 删除文件
来源：http://dali.hywenlv.cn/Article/details/gttuhyspps.html

Py:   os.remove("a.txt")
来源：http://dali.yuanzhike.top/Article/details/gttnilocay.html

PHP:  unlink("a.txt");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdrirlvey.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.hywenlv.cn/Article/details/gtdimbejlh.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtmvvcjfcu.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.xylfe.cn/Article/details/gtqgvkogkj.html

Go:   os.Remove("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtqbxyxemd.html

Ruby: File.delete("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtefjlmglh.html

C#:   File.Delete("a.txt");
来源：http://dali.yj20258.top/Article/details/gtazuqahcy.html

[F07] 创建目录（含多级）
来源：http://dali.cucudq.cn/Article/details/gtpagiyuie.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.chenzaomai.com/Article/details/gtxrhwhnxj.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.wangshuangyany.cn/Article/details/gtimiqnhhz.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.yangfankeji.com/Article/details/gtsnhrxpsa.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.zhijiandao.cn/Article/details/gtzvjuwyqz.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.zhoulong.xyz/Article/details/gtgiflcoad.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.havefunace.top/Article/details/gtysdapoci.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.gotoacloud.top/Article/details/gttmawohuz.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfhwdyfbb.html

[F08] 遍历目录
来源：http://dali.bjfxy.top/Article/details/gtkbwisift.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.xylfe.cn/Article/details/gtyexfnbvj.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.cheryme.top/Article/details/gtrtjonwfy.html

JS:   fs.readdirSync("dir")
来源：http://dali.316326.xyz/Article/details/gtfijnybce.html

TS:   fs.readdirSync("dir")
来源：http://dali.cashguo.top/Article/details/gttwouqazq.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.yongpay.top/Article/details/gtgjmjhogq.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.hfpthk.cn/Article/details/gtdquhabic.html

Ruby: Dir.children("dir")
来源：http://dali.zhijiandao.cn/Article/details/gtvwexecbt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.snrcjt.cn/Article/details/gtzdquledq.html

[F09] 获取文件大小
来源：http://dali.fzhhl.top/Article/details/gtojjkrmyr.html

Py:   os.path.getsize("a.txt")
来源：http://dali.hysaishi.cn/Article/details/gtxdiliozg.html

PHP:  filesize("a.txt");
来源：http://dali.ivvv.top/Article/details/gtgfvufwrn.html

JS:   fs.statSync("a.txt").size
来源：http://dali.cheryme.top/Article/details/gtxxfqlslm.html

TS:   fs.statSync("a.txt").size
来源：http://dali.zhixingplan.top/Article/details/gtmlerogmi.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlspopril.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.hnxiangtu.top/Article/details/gtwacmkyxq.html

Ruby: File.size("a.txt")
来源：http://dali.yueranfly.top/Article/details/gtyxntprtl.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.ivvv.top/Article/details/gtxfgfkyyc.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.yuxming.cn/Article/details/gtegsvqpvs.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.ehwqpu.com/Article/details/gtbkxlblut.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.xylfe.cn/Article/details/gtadnbqmil.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtpjjqobxn.html

TS:   path.extname("a.txt")
来源：http://dali.yvedp.cn/Article/details/gtpuvscadc.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.wangdashe.top/Article/details/gtlgxibwdp.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.guowangkeji.top/Article/details/gtlkkjbwvs.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.snrcjt.cn/Article/details/gtlsokcefo.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.birdmap.top/Article/details/gtijidrmkq.html

[F11] 复制与移动文件
来源：http://dali.gzhubu.top/Article/details/gtrlorlwfa.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.shangyingyoupin.top/Article/details/gtayioxvqv.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.birdmap.top/Article/details/gtecasilri.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.cucudq.cn/Article/details/gttbdfeyng.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.hammf.cn/Article/details/gtqbrxfqma.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.cdnleiting.top/Article/details/gtxdcrkprg.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.cashguo.top/Article/details/gtkpvffdqf.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdqcgdpjp.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.daxiang520.top/Article/details/gtxojuvbwt.html

[F12] CSV 读写
来源：http://dali.iojbl.cn/Article/details/gtjnzfkiil.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.zhixingplan.top/Article/details/gtkigfzadu.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.redwolf501.top/Article/details/gtwiuyfueh.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.andypj.xyz/Article/details/gtuwszptho.html

TS:   // 同上
来源：http://dali.meibo888.top/Article/details/gtzskhtlqq.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.ydzc1.top/Article/details/gtsumnffnp.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.hnqzz.top/Article/details/gtcwgtvmjg.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylcgrnxt.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.nanxinkj.top/Article/details/gttwrnumsx.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgdccgsrm.html

G. 面向对象
来源：http://dali.hammf.cn/Article/details/gtlcjyhkee.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtptbvvuet.html

[G01] 定义类
来源：http://dali.gotoacloud.top/Article/details/gtkxztdfqc.html

Py:   class User: pass
来源：http://dali.jyoumei.cn/Article/details/gtzslhbwxq.html

PHP:  class User {}
来源：http://dali.cashguo.top/Article/details/gtkfffochy.html

JS:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gthlfkimvv.html

TS:   class User { name: string = ""; }
来源：http://dali.yj202588.top/Article/details/gtacxklxwf.html

Java: class User {}
来源：http://dali.316326.xyz/Article/details/gtgobzcigt.html

Go:   type User struct { Name string }
来源：http://dali.316326.xyz/Article/details/gtsfhgirrc.html

Ruby: class User; end
来源：http://dali.gogol.net.cn/Article/details/gtejhawpqm.html

C#:   class User {}
来源：http://dali.nanxinkj.top/Article/details/gtigmcidpl.html

[G02] 构造函数
来源：http://dali.tianlin.xyz/Article/details/gtybsqocbe.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.jinghuilouyu.cn/Article/details/gtobilhhfx.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.andypj.xyz/Article/details/gttdmrkwjr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtvpfkozjp.html

TS:   constructor(public name: string) {}
来源：http://dali.aibaodan.cn/Article/details/gtghnspoul.html

Java: User(String name) { this.name = name; }
来源：http://dali.gzhubu.top/Article/details/gtbabioiyo.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.nanxinkj.top/Article/details/gthnqlieaf.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.hfpthk.cn/Article/details/gtlxzwldsu.html

C#:   public User(string name) { Name = name; }
来源：http://dali.pycfn.com/Article/details/gtriiiknnd.html

[G03] 实例属性
来源：http://dali.jianghu66.top/Article/details/gtcifmjfnc.html

Py:   self.name = "x"
来源：http://dali.redwolf501.top/Article/details/gthvybbnpr.html

PHP:  public string $name = "x";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagfufsfu.html

JS:   this.name = "x";
来源：http://dali.hongshengwenyu.top/Article/details/gttxkalexg.html

TS:   name: string = "x";
来源：http://dali.yj20258888.top/Article/details/gtygmmdwgc.html

Java: private String name;
来源：http://dali.daxiang520.top/Article/details/gtvlbeomad.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.vqdsnc.cn/Article/details/gtbjmalryr.html

Ruby: @name = "x"
来源：http://dali.jiagoushi.top/Article/details/gtvmklwmio.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.nanxuanxn.top/Article/details/gtqeyihhep.html

[G04] 定义方法
来源：http://dali.yj202588.top/Article/details/gtjqmpygny.html

Py:   def greet(self): return self.name
来源：http://dali.316326.xyz/Article/details/gtiockrioy.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.gzhubu.top/Article/details/gtajgnuhex.html

JS:   greet() { return this.name; }
来源：http://dali.xylfe.cn/Article/details/gtlpipktxi.html

TS:   greet(): string { return this.name; }
来源：http://dali.chenlongwang.top/Article/details/gtplgrzdbh.html

Java: String greet() { return name; }
来源：http://dali.jqgufenzy.top/Article/details/gtcrszpbha.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.xziqi.cn/Article/details/gtipkhqurd.html

Ruby: def greet; @name; end
来源：http://dali.chenlongwang.top/Article/details/gtvbcjgsrw.html

C#:   public string Greet() => Name;
来源：http://dali.snrcjt.cn/Article/details/gtrtqksjmh.html

[G05] 继承
来源：http://dali.316326.xyz/Article/details/gtaluyaxcc.html

Py:   class Admin(User): pass
来源：http://dali.havefunace.top/Article/details/gtuccwcyxa.html

PHP:  class Admin extends User {}
来源：http://dali.snrcjt.cn/Article/details/gtgzdmxxeh.html

JS:   class Admin extends User {}
来源：http://dali.xinyue.icu/Article/details/gtozykaazr.html

TS:   class Admin extends User {}
来源：http://dali.yj202588.top/Article/details/gteslealkz.html

Java: class Admin extends User {}
来源：http://dali.ppjwa.cn/Article/details/gtdzmnsalf.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.yj202588.top/Article/details/gtuzikznmj.html

Ruby: class Admin < User; end
来源：http://dali.havefunace.top/Article/details/gtbxcehrpx.html

C#:   class Admin : User {}
来源：http://dali.xylfe.cn/Article/details/gthctnjrzp.html

[G06] 重写方法
来源：http://dali.cdnleiting.top/Article/details/gtoajaqqvg.html

Py:   def greet(self): return "admin"
来源：http://dali.ydzc1.top/Article/details/gtqfdzturv.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.nanxinkj.top/Article/details/gtgvitxrpf.html

JS:   greet() { return "admin"; }
来源：http://dali.9152youxi.cn/Article/details/gtpnvrbeya.html

TS:   greet(): string { return "admin"; }
来源：http://dali.chenzaomai.com/Article/details/gtjmkngnnh.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.aizwys.cn/Article/details/gtnttfrcdb.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.cheryme.top/Article/details/gtfvfcezak.html

Ruby: def greet; "admin"; end
来源：http://dali.jianghu66.top/Article/details/gtlyikfkll.html


<!-- 参考信息 -->