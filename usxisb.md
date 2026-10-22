代发 wailian999

TS:   "7".padStart(3, "0")
来源：http://dali.wangdashe.top/Article/details/gtxczqqqnw.html

Java: String.format("%03d", 7)
来源：http://dali.bjfxy.top/Article/details/gtaxjnwznb.html

Go:   fmt.Sprintf("%03d", 7)
来源：http://dali.ydzc1.top/Article/details/gtcfrddmqw.html

Ruby: 7.to_s.rjust(3, "0");  format("%03d", 7)
来源：http://dali.andypj.xyz/Article/details/gtxkqipczv.html

C#:   7.ToString("D3");  7.ToString().PadLeft(3, '0')
来源：http://dali.jlsjyb.cn/Article/details/gtypkeqidl.html

[E11] 反转字符串
来源：http://dali.hammf.cn/Article/details/gtbjfudatd.html

Py:   s[::-1]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxzygmls.html

PHP:  strrev($s);
来源：http://dali.c1oappe.top/Article/details/gtkqblwofh.html

JS:   [...s].reverse().join("")
来源：http://dali.xylfe.cn/Article/details/gtbotstvid.html

TS:   [...s].reverse().join("")
来源：http://dali.birdmap.top/Article/details/gtbjzbekyo.html

Java: new StringBuilder(s).reverse().toString()
来源：http://dali.yj20258888.top/Article/details/gthktmdcmk.html

Go:   // 转 []rune 后倒序再转回 string
来源：http://dali.daxiang520.top/Article/details/gtltlaqggg.html

Ruby: s.reverse
来源：http://dali.9152youxi.cn/Article/details/gtkngdmtkc.html

C#:   new string(s.Reverse().ToArray())
来源：http://dali.tian-w.cn/Article/details/gtbbejjrko.html

[E12] 统计某字符出现次数
来源：http://dali.meibo888.top/Article/details/gtlpduphsv.html

Py:   s.count("a")
来源：http://dali.meibo888.top/Article/details/gtojjwfhdq.html

PHP:  substr_count($s, "a");
来源：http://dali.ywan-chungtsiang.top/Article/details/gticoztzwv.html

JS:   s.split("a").length - 1
来源：http://dali.guannengcc.top/Article/details/gtztndqtlv.html

TS:   s.split("a").length - 1
来源：http://dali.jyoumei.cn/Article/details/gtxwowajir.html

Java: s.chars().filter(c -> c == 'a').count()
来源：http://dali.nanxuanxn.top/Article/details/gtikalaqsk.html

Go:   strings.Count(s, "a")
来源：http://dali.guannengcc.top/Article/details/gtpticfxoh.html

Ruby: s.count("a")
来源：http://dali.ywan-chungtsiang.top/Article/details/gteusgvivz.html

C#:   s.Count(c => c == 'a')
来源：http://dali.gotoacloud.top/Article/details/gtplwhbrpo.html

[E13] 逐字符遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrxuilkwg.html

Py:   for ch in s: print(ch)
来源：http://dali.jinqigufen.top/Article/details/gtagfqsfcy.html

PHP:  foreach (mb_str_split($s) as $ch) { echo $ch; }
来源：http://dali.vqdsnc.cn/Article/details/gtmgafezdw.html

JS:   for (const ch of s) { console.log(ch); }
来源：http://dali.gotoacloud.top/Article/details/gtiyefgcny.html

TS:   for (const ch of s) { console.log(ch); }
来源：http://dali.ivvv.top/Article/details/gtidwkzqiw.html

Java: for (char ch : s.toCharArray()) { System.out.println(ch); }
来源：http://dali.yj20258888.top/Article/details/gtczfjymkz.html

Go:   for _, ch := range s { fmt.Println(string(ch)) }   // 按 rune 遍历
来源：http://dali.yanxiufei.cn/Article/details/gtscwoszvv.html

Ruby: s.each_char { |ch| puts ch }
来源：http://dali.shuidangran.top/Article/details/gthvghlkds.html

C#:   foreach (var ch in s) { Console.WriteLine(ch); }
来源：http://dali.hysaishi.cn/Article/details/gtwzyhlpjd.html

[E14] URL 编码与 Base64
来源：http://dali.dianchejie.cn/Article/details/gtfqksuvpj.html

Py:   urllib.parse.quote(s);  base64.b64encode(b).decode()
来源：http://dali.jyoumei.cn/Article/details/gtzkpsnjza.html

PHP:  urlencode($s);  base64_encode($s);
来源：http://dali.shuidangran.top/Article/details/gtwrbuyzjo.html

JS:   encodeURIComponent(s);  btoa(s);  atob(b64)
来源：http://dali.pengpengdd.cyou/Article/details/gtqpozpfhm.html

TS:   encodeURIComponent(s);  btoa(s)
来源：http://dali.havefunace.top/Article/details/gtfutmhjla.html

Java: URLEncoder.encode(s, StandardCharsets.UTF_8);  Base64.getEncoder().encodeToString(bytes)
来源：http://dali.quarkkingdee.top/Article/details/gtyhmefogb.html

Go:   url.QueryEscape(s);  base64.StdEncoding.EncodeToString([]byte(s))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbyosvuxu.html

Ruby: URI.encode_www_form_component(s);  [s].pack("m0")
来源：http://dali.c1oappe.top/Article/details/gtlzhmljqg.html

C#:   Uri.EscapeDataString(s);  Convert.ToBase64String(bytes)
来源：http://dali.redwolf501.top/Article/details/gtnpqpopnt.html

[E15] HTML 转义 / 反转义
来源：http://dali.xziqi.cn/Article/details/gtvwdgqzcn.html

Py:   html.escape(s);  html.unescape(s)
来源：http://dali.haohaochexian.top/Article/details/gtnsayfqdn.html

PHP:  htmlspecialchars($s, ENT_QUOTES, "UTF-8");  htmlspecialchars_decode($s);
来源：http://dali.yuanzhike.top/Article/details/gtlxwxbgtc.html

JS:   // 文本节点自动转义；拼接 HTML 时用 DOMPurify.sanitize(s)
来源：http://dali.xziqi.cn/Article/details/gtfnzridxq.html

TS:   // 同上，务必做 XSS 过滤
来源：http://dali.pycfn.com/Article/details/gtdiquudfw.html

Java: HtmlUtils.htmlEscape(s)   // Spring；通用可用 Apache Commons Text
来源：http://dali.cucudq.cn/Article/details/gtactqyxyv.html

Go:   html.EscapeString(s);  html.UnescapeString(s)
来源：http://dali.ehwqpu.com/Article/details/gtubgzhkab.html

Ruby: CGI.escapeHTML(s);  CGI.unescapeHTML(s)
来源：http://dali.jinqigfzy.top/Article/details/gtzirqcero.html

C#:   WebUtility.HtmlEncode(s);  WebUtility.HtmlDecode(s)
来源：http://dali.hnqzz.top/Article/details/gtcxjgbvzp.html

[E16] 数字千分位
来源：http://dali.hywenlv.cn/Article/details/gtcpiwgfpx.html

Py:   f"{1234567:,}"
来源：http://dali.zhiwuduotai.top/Article/details/gtgtuakusp.html

PHP:  number_format(1234567);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwuzzerk.html

JS:   (1234567).toLocaleString("en-US")
来源：http://dali.sxryk.cn/Article/details/gtmceamtqt.html

TS:   (1234567).toLocaleString("en-US")
来源：http://dali.ehwqpu.com/Article/details/gtqghrewlw.html

Java: NumberFormat.getNumberInstance(Locale.US).format(1234567)
来源：http://dali.daria6918.cn/Article/details/gtckumbrjo.html

Go:   // 用 golang.org/x/text/message 或手写分组
来源：http://dali.meibo888.top/Article/details/gtyfrtspcy.html

Ruby: "1234567".reverse.scan(/\d{1,3}/).join(",").reverse
来源：http://dali.tian-w.cn/Article/details/gtecrpepem.html

C#:   1234567.ToString("N0")
来源：http://dali.xinyue.icu/Article/details/gtpgwncstw.html

[E17] 首字母大写
来源：http://dali.xuetiantiany.cn/Article/details/gtqbgnszbj.html

Py:   s[0].upper() + s[1:];  s.capitalize();  s.title()
来源：http://dali.andypj.xyz/Article/details/gtberpdxpo.html

PHP:  ucfirst($s);  ucwords($s);
来源：http://dali.meibo888.top/Article/details/gtixuzuxgz.html

JS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.cucudq.cn/Article/details/gtlnfhwqba.html

TS:   s.charAt(0).toUpperCase() + s.slice(1)
来源：http://dali.bjfxy.top/Article/details/gtneyfgume.html

Java: Character.toUpperCase(s.charAt(0)) + s.substring(1)
来源：http://dali.zycfv.cn/Article/details/gtpafccvnj.html

Go:   strings.ToUpper(s[:1]) + s[1:]
来源：http://dali.sufxvd.cn/Article/details/gtegzxuqab.html

Ruby: s.capitalize
来源：http://dali.hammf.cn/Article/details/gtencrfnlk.html

C#:   char.ToUpper(s[0]) + s[1..]
来源：http://dali.jinqigfzy.top/Article/details/gttcirjnfp.html

[E18] 模板占位符替换
来源：http://dali.birdmap.top/Article/details/gtvdggntjo.html

Py:   "Hello, {name}".format(name="A");  tpl.replace("{name}", "A")
来源：http://dali.aibaodan.cn/Article/details/gthhyohflr.html

PHP:  str_replace("{name}", "A", $tpl);  sprintf("Hello, %s", $name);
来源：http://dali.zhengqikj.top/Article/details/gtzsmgnkmn.html

JS:   tpl.replaceAll("{name}", name)
来源：http://dali.gzhubu.top/Article/details/gtkuotbryg.html

TS:   tpl.replaceAll("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtpwhgikez.html

Java: "Hello, %s".formatted(name);  tpl.replace("{name}", name)
来源：http://dali.0kj1m.cn/Article/details/gtmpylvdvq.html

Go:   strings.ReplaceAll(tpl, "{name}", name)
来源：http://dali.chenzaomai.com/Article/details/gtdrbeofwj.html

Ruby: tpl.gsub("{name}", name);  "Hello, #{name}"
来源：http://dali.haohaochexian.top/Article/details/gtbrepxwkz.html

C#:   tpl.Replace("{name}", name);  $"Hello, {name}"
来源：http://dali.pengpengdd.cyou/Article/details/gtfbkteuvf.html

[E19] 多行文本按行拆分
来源：http://dali.feifeiyinyue.top/Article/details/gtpmgkfmql.html

Py:   s.splitlines()
来源：http://dali.zhixingplan.top/Article/details/gtzkdzxffc.html

PHP:  preg_split('/\r\n|\r|\n/', $s);
来源：http://dali.gogol.net.cn/Article/details/gtaeeztvcx.html

JS:   s.split(/\r?\n/)
来源：http://dali.ybcxt.top/Article/details/gtycurwfcu.html

TS:   s.split(/\r?\n/)
来源：http://dali.fzhhl.top/Article/details/gtfzgjtclv.html

Java: s.lines().toList()
来源：http://dali.fengsongda.top/Article/details/gthcptfwbs.html

Go:   strings.Split(s, "\n")
来源：http://dali.ybcxt.top/Article/details/gtqpwyzfqt.html

Ruby: s.lines
来源：http://dali.zhoulong.xyz/Article/details/gtaduddckb.html

C#:   s.Split('\n')
来源：http://dali.zdqjudy.top/Article/details/gtqvcyookl.html

[E20] 判断字符串是否为空
来源：http://dali.pengpengdd.cyou/Article/details/gtqwcswkhe.html

Py:   if not s:
来源：http://dali.zdqjudy.top/Article/details/gtppasxznj.html

PHP:  if ($s === "") {}      // 注意 empty("0") 也为 true
来源：http://dali.0kj1m.cn/Article/details/gtkooxioxs.html

JS:   if (s === "") {} 或 if (!s) {}
来源：http://dali.xziqi.cn/Article/details/gtmksbukcm.html

TS:   if (s === "") {}
来源：http://dali.guowangkeji.top/Article/details/gtdpvrnavd.html

Java: if (s.isEmpty()) {}
来源：http://dali.zhijiandao.cn/Article/details/gtbrwpfzwz.html

Go:   if s == "" {}
来源：http://dali.yvedp.cn/Article/details/gtxusmgund.html

Ruby: if s.empty?
来源：http://dali.gogol.net.cn/Article/details/gtfptacbrp.html

C#:   if (string.IsNullOrEmpty(s)) {}
来源：http://dali.sysykeji.top/Article/details/gtumbtnbkh.html

[E21] 超长截断加省略号
来源：http://dali.nwbrower.top/Article/details/gthenrjtwj.html

Py:   (s[:20] + "…") if len(s) > 20 else s
来源：http://dali.gogol.net.cn/Article/details/gtphnjanvk.html

PHP:  mb_strimwidth($s, 0, 20, "…", "UTF-8");
来源：http://dali.shuidangran.top/Article/details/gtzolkldrn.html

JS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.ivvv.top/Article/details/gtlatgzspw.html

TS:   s.length > 20 ? s.slice(0, 20) + "…" : s
来源：http://dali.jyoumei.cn/Article/details/gtrvacvcrp.html

Java: s.length() > 20 ? s.substring(0, 20) + "…" : s
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlhjypiig.html

Go:   // 按 rune 判断长度后截断
来源：http://dali.chenjidiqi.icu/Article/details/gtzijldcxt.html

Ruby: s.length > 20 ? s[0, 20] + "…" : s
来源：http://dali.hysaishi.cn/Article/details/gtksnxeoht.html

C#:   s.Length > 20 ? s[..20] + "…" : s
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtedbsxjie.html

[E22] 字节长度与字符长度
来源：http://dali.zhixingplan.top/Article/details/gtqesutkyr.html

Py:   len(s.encode("utf-8"));  len(s)
来源：http://dali.ehwqpu.com/Article/details/gtrjyelweb.html

PHP:  strlen($s);  mb_strlen($s, "UTF-8");
来源：http://dali.yanxiufei.cn/Article/details/gtezennodm.html

JS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdoildcmo.html

TS:   new TextEncoder().encode(s).length;  s.length
来源：http://dali.jinqigufen.top/Article/details/gtwfmyozdx.html

Java: s.getBytes(StandardCharsets.UTF_8).length;  s.length()
来源：http://dali.guannengcc.top/Article/details/gtmjaeopdf.html

Go:   len(s);  utf8.RuneCountInString(s)     # 前者字节数，后者字符数
来源：http://dali.hnqzz.top/Article/details/gtmtqkjlra.html

Ruby: s.bytesize;  s.length
来源：http://dali.haohaochexian.top/Article/details/gttluwsjtu.html

C#:   Encoding.UTF8.GetByteCount(s);  s.Length
来源：http://dali.dashuyun.cn/Article/details/gtbvtvwwuq.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtcjheafkb.html

F. 文件与目录
来源：http://dali.cucudq.cn/Article/details/gtsklrtgot.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbnrlsnb.html

[F01] 读取整个文件
来源：http://dali.zycfv.cn/Article/details/gtxwtiggjm.html

Py:   open("a.txt", encoding="utf-8").read();  Path("a.txt").read_text()
来源：http://dali.gogol.net.cn/Article/details/gtoqudtxre.html

PHP:  file_get_contents("a.txt");
来源：http://dali.yuanzhike.top/Article/details/gtoxanopqg.html

JS:   fs.readFileSync("a.txt", "utf8")          // Node.js
来源：http://dali.shangyingyoupin.top/Article/details/gtjncfaiov.html

TS:   fs.readFileSync("a.txt", "utf8")
来源：http://dali.redwolf501.top/Article/details/gthdxyzcje.html

Java: Files.readString(Path.of("a.txt"))
来源：http://dali.aibaodan.cn/Article/details/gteuqfqcha.html

Go:   data, err := os.ReadFile("a.txt")        // []byte，用 string(data) 转文本
来源：http://dali.ybcxt.top/Article/details/gtpnynapar.html

Ruby: File.read("a.txt")
来源：http://dali.svipenyu.cn/Article/details/gtifinpetf.html

C#:   File.ReadAllText("a.txt");
来源：http://dali.cqqwz.cn/Article/details/gthaqqjbhh.html

[F02] 逐行读取文件
来源：http://dali.aibaodan.cn/Article/details/gtijhfhqnq.html

Py:   for line in open("a.txt", encoding="utf-8"): print(line.rstrip())
来源：http://dali.hongshengwenyu.top/Article/details/gtnwfpmpbm.html

PHP:  foreach (file("a.txt", FILE_IGNORE_NEW_LINES) as $line) { echo $line; }
来源：http://dali.haohaochexian.top/Article/details/gtwtyeixcz.html

JS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.fzhhl.top/Article/details/gthegsxzkr.html

TS:   for (const line of fs.readFileSync("a.txt", "utf8").split("\n")) {}
来源：http://dali.birdmap.top/Article/details/gtydikvojj.html

Java: Files.lines(Path.of("a.txt")).forEach(System.out::println)
来源：http://dali.c1oappe.top/Article/details/gticfpujdj.html

Go:   scanner := bufio.NewScanner(f); for scanner.Scan() { fmt.Println(scanner.Text()) }
来源：http://dali.redwolf501.top/Article/details/gtftrkbxyi.html

Ruby: File.foreach("a.txt") { |line| puts line }
来源：http://dali.meibo888.top/Article/details/gtqpykdeqe.html

C#:   foreach (var line in File.ReadLines("a.txt")) { Console.WriteLine(line); }
来源：http://dali.nwbrower.top/Article/details/gtyrjpuygb.html

[F03] 写入文件（覆盖）
来源：http://dali.chenlongwang.top/Article/details/gtmobqsywh.html

Py:   open("a.txt", "w", encoding="utf-8").write("hi")
来源：http://dali.guannengcc.top/Article/details/gtulsvxdgs.html

PHP:  file_put_contents("a.txt", "hi");
来源：http://dali.hfpthk.cn/Article/details/gtvknmextf.html

JS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.shzxlz.cn/Article/details/gtcupotnzj.html

TS:   fs.writeFileSync("a.txt", "hi", "utf8")
来源：http://dali.0kj1m.cn/Article/details/gtbeornyne.html

Java: Files.writeString(Path.of("a.txt"), "hi")
来源：http://dali.svipenyu.cn/Article/details/gtnirtctnd.html

Go:   os.WriteFile("a.txt", []byte("hi"), 0644)
来源：http://dali.jiagoushi.top/Article/details/gtxfgbxnxw.html

Ruby: File.write("a.txt", "hi")
来源：http://dali.zycfv.cn/Article/details/gtflfkrepj.html

C#:   File.WriteAllText("a.txt", "hi");
来源：http://dali.fengsongda.top/Article/details/gtadbawddo.html

[F04] 追加写入文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpluydrrw.html

Py:   open("a.txt", "a", encoding="utf-8").write("more\n")
来源：http://dali.gogol.net.cn/Article/details/gtwlinkunz.html

PHP:  file_put_contents("a.txt", "more\n", FILE_APPEND);
来源：http://dali.yuanzhike.top/Article/details/gttvbqrxdu.html

JS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.dashuyun.cn/Article/details/gtxuuyfwpf.html

TS:   fs.appendFileSync("a.txt", "more\n")
来源：http://dali.jinqigufen.top/Article/details/gtynmqukae.html

Java: Files.writeString(Path.of("a.txt"), "more\n", StandardOpenOption.APPEND)
来源：http://dali.fzhhl.top/Article/details/gtxpzxjoln.html

Go:   f, _ := os.OpenFile("a.txt", os.O_APPEND|os.O_WRONLY, 0644); f.WriteString("more\n")
来源：http://dali.yonumen.top/Article/details/gtcpjvwoii.html

Ruby: File.open("a.txt", "a") { |f| f.puts "more" }
来源：http://dali.shangyingyoupin.top/Article/details/gtzedxwoga.html

C#:   File.AppendAllText("a.txt", "more\n");
来源：http://dali.cucudq.cn/Article/details/gtzxoqxynt.html

[F05] 判断文件或目录是否存在
来源：http://dali.mhx1999.top/Article/details/gtrcxxlcwn.html

Py:   os.path.exists("a.txt");  Path("a.txt").exists()
来源：http://dali.havefunace.top/Article/details/gtynmsnssi.html

PHP:  file_exists("a.txt");
来源：http://dali.cheryme.top/Article/details/gtfgsitlsp.html

JS:   fs.existsSync("a.txt")
来源：http://dali.zycfv.cn/Article/details/gtesvlhcwv.html

TS:   fs.existsSync("a.txt")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcjvburm.html

Java: Files.exists(Path.of("a.txt"))
来源：http://dali.jqgufenzy.top/Article/details/gtdhdjwaim.html

Go:   if _, err := os.Stat("a.txt"); err == nil { /* 存在 */ }
来源：http://dali.gogol.net.cn/Article/details/gtkbksnxdt.html

Ruby: File.exist?("a.txt")
来源：http://dali.yongpay.top/Article/details/gtafrllvnh.html

C#:   File.Exists("a.txt")
来源：http://dali.wangdashe.top/Article/details/gtqhtkcuks.html

[F06] 删除文件
来源：http://dali.yj20258.top/Article/details/gtarpulhxg.html

Py:   os.remove("a.txt")
来源：http://dali.gaohongyu789.top/Article/details/gtghjmqein.html

PHP:  unlink("a.txt");
来源：http://dali.jiagoushi.top/Article/details/gtykfpeytf.html

JS:   fs.unlinkSync("a.txt")
来源：http://dali.zhongyouzk.top/Article/details/gtnmjatsbg.html

TS:   fs.unlinkSync("a.txt")
来源：http://dali.snrcjt.cn/Article/details/gttlprhzep.html

Java: Files.deleteIfExists(Path.of("a.txt"))
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgvqswmko.html

Go:   os.Remove("a.txt")
来源：http://dali.guannengcc.top/Article/details/gtncfrgcde.html

Ruby: File.delete("a.txt")
来源：http://dali.316326.xyz/Article/details/gtohdfnwsd.html

C#:   File.Delete("a.txt");
来源：http://dali.zhiwuduotai.top/Article/details/gtlvmlpfys.html

[F07] 创建目录（含多级）
来源：http://dali.gzhubu.top/Article/details/gtogbdwrtp.html

Py:   os.makedirs("dir/sub", exist_ok=True)
来源：http://dali.jiagoushi.top/Article/details/gtcboeiidh.html

PHP:  mkdir("dir/sub", 0777, true);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrdkrwdqs.html

JS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.sysykeji.top/Article/details/gteoqchrmj.html

TS:   fs.mkdirSync("dir/sub", { recursive: true })
来源：http://dali.316326.xyz/Article/details/gtftivrzph.html

Java: Files.createDirectories(Path.of("dir/sub"))
来源：http://dali.sxryk.cn/Article/details/gtatooarmp.html

Go:   os.MkdirAll("dir/sub", 0755)
来源：http://dali.shzxlz.cn/Article/details/gtxjvcxkla.html

Ruby: FileUtils.mkdir_p("dir/sub")
来源：http://dali.quarkkingdee.top/Article/details/gtznhckkel.html

C#:   Directory.CreateDirectory("dir/sub");
来源：http://dali.yj20258888.top/Article/details/gtniiymwlt.html

[F08] 遍历目录
来源：http://dali.gotoacloud.top/Article/details/gtvtbphrkv.html

Py:   for name in os.listdir("dir"): print(name)
来源：http://dali.ybcxt.top/Article/details/gttunjpqow.html

PHP:  foreach (scandir("dir") as $f) { echo $f; }
来源：http://dali.jiagoushi.top/Article/details/gtsdrmqxqf.html

JS:   fs.readdirSync("dir")
来源：http://dali.yj20258.top/Article/details/gtqtrmnkxd.html

TS:   fs.readdirSync("dir")
来源：http://dali.jqgfzy.top/Article/details/gthhentwri.html

Java: Files.list(Path.of("dir")).forEach(System.out::println)
来源：http://dali.shuidangran.top/Article/details/gtlkxruqdh.html

Go:   entries, _ := os.ReadDir("dir")
来源：http://dali.aizwys.cn/Article/details/gtshegngjv.html

Ruby: Dir.children("dir")
来源：http://dali.yuxming.cn/Article/details/gtkpuletkt.html

C#:   Directory.GetFiles("dir")
来源：http://dali.jyoumei.cn/Article/details/gtusqhjrxm.html

[F09] 获取文件大小
来源：http://dali.hongshengwenyu.top/Article/details/gthsjqepzm.html

Py:   os.path.getsize("a.txt")
来源：http://dali.yanxiufei.cn/Article/details/gtqgovtjgv.html

PHP:  filesize("a.txt");
来源：http://dali.hfpthk.cn/Article/details/gtvupndrdm.html

JS:   fs.statSync("a.txt").size
来源：http://dali.smart0.xyz/Article/details/gtbramgpdz.html

TS:   fs.statSync("a.txt").size
来源：http://dali.yangfankeji.com/Article/details/gtcmphkmxq.html

Java: Files.size(Path.of("a.txt"))
来源：http://dali.cqqwz.cn/Article/details/gtawuktqrq.html

Go:   info, _ := os.Stat("a.txt"); info.Size()
来源：http://dali.yj20258.top/Article/details/gtbglgkssv.html

Ruby: File.size("a.txt")
来源：http://dali.cashguo.top/Article/details/gtpqgagdwu.html

C#:   new FileInfo("a.txt").Length
来源：http://dali.zhixingplan.top/Article/details/gtsxhkgmbl.html

[F10] 取文件扩展名 / 文件名
来源：http://dali.cucudq.cn/Article/details/gtmoagvfyg.html

Py:   os.path.splitext("a.txt");  os.path.basename("/x/a.txt")
来源：http://dali.pengpengdd.cyou/Article/details/gttcowwuhq.html

PHP:  pathinfo("a.txt", PATHINFO_EXTENSION);  basename("/x/a.txt");
来源：http://dali.sysykeji.top/Article/details/gtyulcwyse.html

JS:   path.extname("a.txt");  path.basename("/x/a.txt")
来源：http://dali.gzhubu.top/Article/details/gtzrssgbop.html

TS:   path.extname("a.txt")
来源：http://dali.tianlin.xyz/Article/details/gtrqiafhyg.html

Java: // 手动 substring(lastIndexOf('.'))
来源：http://dali.0kj1m.cn/Article/details/gthclgmnih.html

Go:   filepath.Ext("a.txt");  filepath.Base("/x/a.txt")
来源：http://dali.jqgufenzy.top/Article/details/gtkrwzlksl.html

Ruby: File.extname("a.txt");  File.basename("/x/a.txt")
来源：http://dali.daria6918.cn/Article/details/gtearktgkq.html

C#:   Path.GetExtension("a.txt");  Path.GetFileName("/x/a.txt")
来源：http://dali.pycfn.com/Article/details/gtbdkrtneq.html

[F11] 复制与移动文件
来源：http://dali.nanxinkj.top/Article/details/gtgdlatyru.html

Py:   shutil.copy("a.txt", "b.txt");  shutil.move("a.txt", "b.txt")
来源：http://dali.fzhhl.top/Article/details/gtdjveqtnt.html

PHP:  copy("a.txt", "b.txt");  rename("a.txt", "b.txt");
来源：http://dali.yonumen.top/Article/details/gtudhmxans.html

JS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.vqdsnc.cn/Article/details/gtoarngrte.html

TS:   fs.copyFileSync("a.txt", "b.txt");  fs.renameSync("a.txt", "b.txt")
来源：http://dali.zhoulong.xyz/Article/details/gtvqpjenud.html

Java: Files.copy(Path.of("a"), Path.of("b"));  Files.move(a, b)
来源：http://dali.hysaishi.cn/Article/details/gthdneobfi.html

Go:   data, _ := os.ReadFile("a.txt"); os.WriteFile("b.txt", data, 0644)   // 移动用 os.Rename
来源：http://dali.chenzaomai.com/Article/details/gtynhryxxe.html

Ruby: FileUtils.cp("a.txt", "b.txt");  FileUtils.mv("a.txt", "b.txt")
来源：http://dali.snrcjt.cn/Article/details/gtjhtxubex.html

C#:   File.Copy("a", "b", true);  File.Move("a", "b", true);
来源：http://dali.pycfn.com/Article/details/gteqinzazz.html

[F12] CSV 读写
来源：http://dali.tanke756.top/Article/details/gtwilaiioo.html

Py:   csv.reader(open("a.csv"));  csv.writer(f).writerow(row)
来源：http://dali.yuanzhike.top/Article/details/gtornugoxw.html

PHP:  $rows = array_map("str_getcsv", file("a.csv"));
来源：http://dali.ydzc1.top/Article/details/gtjzintatn.html

JS:   // 无内置：按行 split(",")，复杂场景用 csv-parse 库
来源：http://dali.316326.xyz/Article/details/gtaznlnfir.html

TS:   // 同上
来源：http://dali.zhiwuduotai.top/Article/details/gtxtoqravw.html

Java: // 无内置：用 OpenCSV / Apache Commons CSV
来源：http://dali.pycfn.com/Article/details/gtmooovgsz.html

Go:   csv.NewReader(f).ReadAll()        // encoding/csv
来源：http://dali.c1oappe.top/Article/details/gtxljuazaf.html

Ruby: CSV.read("a.csv")                 // require "csv"
来源：http://dali.jlsjyb.cn/Article/details/gtvzsrxlbg.html

C#:   // 无内置：用 CsvHelper 库
来源：http://dali.cheryme.top/Article/details/gtmkakuknw.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gthfpocbps.html

G. 面向对象
来源：http://dali.wangdashe.top/Article/details/gtejfwegcs.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgnjtjsdv.html

[G01] 定义类
来源：http://dali.jinghuilouyu.cn/Article/details/gtypsgsicf.html

Py:   class User: pass
来源：http://dali.shzxlz.cn/Article/details/gtjfbsmfhq.html

PHP:  class User {}
来源：http://dali.tanke756.top/Article/details/gtaywatihx.html

JS:   class User {}
来源：http://dali.yj202588.top/Article/details/gtspdloueo.html

TS:   class User { name: string = ""; }
来源：http://dali.wangdashe.top/Article/details/gtgzyxcvfh.html

Java: class User {}
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrlwkexyv.html

Go:   type User struct { Name string }
来源：http://dali.aizwys.cn/Article/details/gtaiwwxgqm.html

Ruby: class User; end
来源：http://dali.shuidangran.top/Article/details/gtpkijiblq.html

C#:   class User {}
来源：http://dali.zhiwuduotai.top/Article/details/gtwyicnbxq.html

[G02] 构造函数
来源：http://dali.birdmap.top/Article/details/gtlrgpiurt.html

Py:   def __init__(self, name): self.name = name
来源：http://dali.xuanzx.com/Article/details/gtijsfgxkm.html

PHP:  public function __construct(public string $name) {}
来源：http://dali.xuetiantiany.cn/Article/details/gthgyafxqr.html

JS:   constructor(name) { this.name = name; }
来源：http://dali.ydzc1.top/Article/details/gtouxyppby.html

TS:   constructor(public name: string) {}
来源：http://dali.meibo888.top/Article/details/gttfxwvtds.html

Java: User(String name) { this.name = name; }
来源：http://dali.svipenyu.cn/Article/details/gtatwkondz.html

Go:   func NewUser(name string) *User { return &User{Name: name} }
来源：http://dali.aibaodan.cn/Article/details/gtxglozrzy.html

Ruby: def initialize(name); @name = name; end
来源：http://dali.quarkkingdee.top/Article/details/gtmclifrgo.html

C#:   public User(string name) { Name = name; }
来源：http://dali.jinqigfzy.top/Article/details/gthvsxgnom.html

[G03] 实例属性
来源：http://dali.xuetiantiany.cn/Article/details/gtcesrvodk.html

Py:   self.name = "x"
来源：http://dali.birdmap.top/Article/details/gthtruhgsi.html

PHP:  public string $name = "x";
来源：http://dali.hnxiangtu.top/Article/details/gtegbmdkhf.html

JS:   this.name = "x";
来源：http://dali.daxiang520.top/Article/details/gtmynbrmbm.html

TS:   name: string = "x";
来源：http://dali.redwolf501.top/Article/details/gtfwoykuwe.html

Java: private String name;
来源：http://dali.sufxvd.cn/Article/details/gtjqbvvrzt.html

Go:   u := User{Name: "x"}         // 结构体字段
来源：http://dali.fzhhl.top/Article/details/gtetonpiws.html

Ruby: @name = "x"
来源：http://dali.zhengqikj.top/Article/details/gtezktalqw.html

C#:   public string Name { get; set; } = "x";
来源：http://dali.yuanzhike.top/Article/details/gtlwnenoiz.html

[G04] 定义方法
来源：http://dali.wangshuangyany.cn/Article/details/gtjxlcbclj.html

Py:   def greet(self): return self.name
来源：http://dali.snrcjt.cn/Article/details/gtklkaxcua.html

PHP:  public function greet(): string { return $this->name; }
来源：http://dali.yanxiufei.cn/Article/details/gtrgltexna.html

JS:   greet() { return this.name; }
来源：http://dali.zhengqikj.top/Article/details/gtutaxyime.html

TS:   greet(): string { return this.name; }
来源：http://dali.zhoulong.xyz/Article/details/gtjknivfea.html

Java: String greet() { return name; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcqlrogju.html

Go:   func (u User) Greet() string { return u.Name }
来源：http://dali.yongpay.top/Article/details/gteunhvwja.html

Ruby: def greet; @name; end
来源：http://dali.sxryk.cn/Article/details/gtihidnuuy.html

C#:   public string Greet() => Name;
来源：http://dali.cashguo.top/Article/details/gtdwtsrpba.html

[G05] 继承
来源：http://dali.dashuyun.cn/Article/details/gtsnegmswv.html

Py:   class Admin(User): pass
来源：http://dali.xylfe.cn/Article/details/gtzmnwywgc.html

PHP:  class Admin extends User {}
来源：http://dali.vqdsnc.cn/Article/details/gtxtlrxguy.html

JS:   class Admin extends User {}
来源：http://dali.chenjidiqi.icu/Article/details/gtiutjijny.html

TS:   class Admin extends User {}
来源：http://dali.wangshuangyany.cn/Article/details/gttqxzhkfp.html

Java: class Admin extends User {}
来源：http://dali.yvedp.cn/Article/details/gtytggqtqt.html

Go:   type Admin struct { User }     // 用嵌入代替继承
来源：http://dali.sweek.top/Article/details/gttiizgafk.html

Ruby: class Admin < User; end
来源：http://dali.mhx1999.top/Article/details/gtccckjzhh.html

C#:   class Admin : User {}
来源：http://dali.pycfn.com/Article/details/gtvxjmhdph.html

[G06] 重写方法
来源：http://dali.quarkkingdee.top/Article/details/gtmzezvcgq.html

Py:   def greet(self): return "admin"
来源：http://dali.cashguo.top/Article/details/gtpqcsoygs.html

PHP:  public function greet(): string { return "admin"; }
来源：http://dali.zhixingplan.top/Article/details/gtskbxlnfh.html

JS:   greet() { return "admin"; }
来源：http://dali.0kj1m.cn/Article/details/gtbgabcssj.html

TS:   greet(): string { return "admin"; }
来源：http://dali.yuanzhike.top/Article/details/gtfdlbxlsb.html

Java: @Override String greet() { return "admin"; }
来源：http://dali.ppjwa.cn/Article/details/gtkgbmjbcf.html

Go:   // 嵌入类型定义同名方法即覆盖
来源：http://dali.yueranfly.top/Article/details/gtarlgymjr.html

Ruby: def greet; "admin"; end
来源：http://dali.cheryme.top/Article/details/gtaauuupne.html

C#:   public override string Greet() => "admin";
来源：http://dali.gotoacloud.top/Article/details/gtgfzqfkaj.html

[G07] 调用父类方法
来源：http://dali.guowangkeji.top/Article/details/gtqsoxnkce.html

Py:   super().greet()
来源：http://dali.birdmap.top/Article/details/gtqutmvdpi.html

PHP:  parent::greet();
来源：http://dali.gotoacloud.top/Article/details/gtnmzplcze.html

JS:   super.greet();
来源：http://dali.zhongyouzk.top/Article/details/gtlfihaexz.html

TS:   super.greet();
来源：http://dali.dashuyun.cn/Article/details/gtorhlliqt.html

Java: super.greet();
来源：http://dali.yonumen.top/Article/details/gtanwwqrlz.html

Go:   u.User.Greet()               // 显式调用嵌入字段的方法
来源：http://dali.ybcxt.top/Article/details/gteiomskwo.html

Ruby: super
来源：http://dali.hammf.cn/Article/details/gtzpzsgnkz.html

C#:   base.Greet();
来源：http://dali.zhiwuduotai.top/Article/details/gthmzvkqfy.html

[G08] 静态方法与属性
来源：http://dali.zhaomingkeji.xyz/Article/details/gtioewqrav.html

Py:   @staticmethod⏎def f(): ...      # 类方法用 @classmethod，首个参数为 cls
来源：http://dali.iojbl.cn/Article/details/gtyekaoxzk.html

PHP:  public static function f() {}
来源：http://dali.haohaochexian.top/Article/details/gtydkixhxg.html

JS:   static f() {}
来源：http://dali.birdmap.top/Article/details/gtoeqlmuep.html

TS:   static f(): void {}
来源：http://dali.ywan-chungtsiang.top/Article/details/gtntdtbyaw.html

Java: static void f() {}
来源：http://dali.9152youxi.cn/Article/details/gtgnemhfui.html

Go:   // 无 static：用包级函数，按包名调用
来源：http://dali.jinghuilouyu.cn/Article/details/gtzkkvidmp.html

Ruby: def self.f; end
来源：http://dali.xinyue.icu/Article/details/gtzfgrnqnt.html

C#:   public static void F() {}
来源：http://dali.tian-w.cn/Article/details/gtxtovrbap.html

[G09] 接口 / 抽象类
来源：http://dali.sweek.top/Article/details/gtrqluupjn.html


<!-- 参考信息 -->